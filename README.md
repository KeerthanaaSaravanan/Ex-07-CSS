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

# HTML CODE: 7(i)
```
<!DOCTYPE html>
<html>
<head>
    <title>My Web Page</title>
    <link rel="stylesheet" type="text/css" href="default.css">
</head>
<body>
    <h1>Welcome to My Web Page!</h1>
    <p>This is a paragraph of text. Here are some important links:</p>
    <ul>
        <li><a href="https://www.bing.com">Bing Search</a></li>
        <li><a href="https://www.microsoft.com">Microsoft</a></li>
        <li><a href="https://www.github.com">GitHub</a></li>
    </ul>
</body>
</html>
```

# CSS CODE: 7(i)
```
/* Default Color Scheme */
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

```

# OUTPUT:7(i):


# Ex-07(ii)-CSS

# AIM

To use a media query in CSS to apply different styles to a webpage for mobile devices (with widths less than 600px) and desktop devices (with widths greater than or equal to 600px) by providing an example CSS snippet to demonstrate your answer.

# DESIGN STEPS: 7(ii)
## Step 1:

Styles for Mobile Devices (Width < 600px):
Use a media query with (max-width: 599px) to target devices with a maximum width of 599 pixels.

## Step 2:

Styles for Desktop Devices (Width >= 600px):
Use a media query with (min-width: 600px) to target devices with a minimum width of 600 pixels.


# HTML CODE: 7(ii)
```

```

# CSS CODE: 7(ii)
```


```

# OUTPUT:7(ii):

 
# Ex-07(iii)-CSS Orientation-based Media Query

# AIM

To explain how you can use CSS media queries to apply different styles based on the orientation (landscape or portrait) of the device. Provide a CSS example where you change the background color of the body based on the orientation.

# DESIGN STEPS: 7(iii)
## Step 1:

Set default Styles:
Set the default background color for the body to #f0f0f0.
Set the default text color to #333.

## Step 2:

Media Query for Landscape Orientation:
Check if the device is in landscape orientation using the @media rule and the orientation: landscape condition.

## Step 3:

Media Query for Portrait Orientation:
Check if the device is in portrait orientation using the @media rule and the orientation: portrait condition.

# HTML CODE: 7(iii)
```

```

# CSS CODE: 7(iii)
```


```

# OUTPUT:7(iii):



# Ex-07(iv)-CSS Responsive Typography

# AIM

To describe how you would use media queries to adjust typography (like font size and line spacing) on a website to improve readability across different device sizes, from mobile phones to large desktop monitors. Include a CSS code snippet in your explanation.

# DESIGN STEPS: 7(iv)
## Step 1:

Set Default Typography Styles

## Step 2:

Define Media Queries for Different Screen Sizes

## Step 3:

Adjust Typography Styles Within Media Queries

# HTML CODE: 7(iv)
```

```

# CSS CODE: 7(iv)
```

```

# OUTPUT:7(iv):



# Ex-07(v)-Print-friendly CSS

# AIM

To use a media query to change the styling of a webpage when it is printed, such as changing the background to white and hiding non-essential elements? Provide a CSS example.

# DESIGN STEPS: 7(v)
## Step 1:
Set Default Webpage Styles

## Step 2:
Define Media Query for Print Styles

## Step 3:
Adjust Styles for Printing

# HTML CODE: 7(v)
```

```

# CSS CODE: 7(v)
```

```

# OUTPUT:7(v):



# Ex-07(vi)-Dark Mode Implementation

# AIM

With the increasing popularity of dark mode in user interfaces, explain how you would use a media query to detect if the user has set their system to prefer a dark color scheme. Provide an example of how you would change the background and text colors of a website based on this preference.

# DESIGN STEPS: 7(vi)
## Step 1:
Set Default Webpage Styles

## Step 2:
Define Media Query for Dark Mode

## Step 3:
Adjust Styles for Dark Mode

# HTML CODE: 7(vi)
```

```

# CSS CODE: 7(vi)
```

  

```

# OUTPUT:7(vi):




