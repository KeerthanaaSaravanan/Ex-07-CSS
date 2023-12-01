# Ex-07(i)-CSS

# AIM
Using CSS media queries, modify the webpage's color scheme with the following requirements:

Default Color Scheme:

Background color: Light gray (#f4f4f4)

Text color: Dark gray (#333)

Link color: Blue (#007bff)

Small Screen Adaptation (Max-width: 600px):


Change the background color to dark gray (#333)

Change the text color to light gray (#f4f4f4)

Change the link color to light green (#28a745)

Dark Mode Preference:


If the user has set their device to dark mode, override the above styles with the following:

Background color: Black (#000)

Text color: White (#fff)

Link color: Cyan (#17a2b8)

# DESIGN STEPS: 7(i)
## Step 1:

Set Default Color Scheme

## Step 2:

Small Screen Adaptation (Max-width: 600px)

## Step 3:

Dark Mode Preference:

Use a media query with (prefers-color-scheme: dark) to target devices set to dark mode.

# HTML PROGRAM CODE: 7(i)
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple HTML Program</title>
<link rel="stylesheet" type="text/css" href="default.css">
  <style>
    body {
      font-family: 'Arial', sans-serif;
      text-align: center;
      margin: 20px;
    }

    h1 {
      color:white;
    }

    p {
      color: white;
    }
  </style>
</head>

<body>
  <h1>Welcome to My Simple HTML Program</h1>
  <p>This is a basic HTML document.</p>
</body>
</html>

# CSS PROGRAM CODE: 7(i)
/* Default styles */
body {
    background-color: #f4f4f4;
    color: #333;
  }
  
  a {
    color: #007bff;
  }
  
  /* Small Screen Adaptation */
  @media (max-width: 600px) {
    body {
      background-color: #333;
      color: #f4f4f4;
    }
  
    a {
      color: #28a745;
    }
  }
  
  /* Dark Mode Preference */
  @media (prefers-color-scheme: dark) {
    body {
      background-color: #000;
      color: #fff;
    }
  
    a {
      color: #17a2b8;
    }
  }
  

# OUTPUT:7(i):

![Alt text](7(i)_OUTPUT.png)
