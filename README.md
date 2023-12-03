# Ex-07-CSS

## AIM :
Using CSS media queries, modify the webpage's color scheme with the following requirements:

Default Color Scheme: Background color: Light gray (#f4f4f4) Text color: Dark gray (#333) Link color: Blue (#007bff) Small Screen Adaptation (Max-width: 600px):

Change the background color to dark gray (#333) Change the text color to light gray (#f4f4f4) Change the link color to light green (#28a745)

Dark Mode Preference:

If the user has set their device to dark mode, override the above styles with the following: Background color: Black (#000) Text color: White (#fff) Link color: Cyan (#17a2b8)

## DESIGN STEPS: 7(i):

## step 1:

Start Define the document type as HTML.

## step 2:

Open the HTML structure with the necessary head and body sections. In the head section, set the title of the webpage and define the styles for the webpage. The styles include: -->Default color scheme for the webpage. -->Adaptations for small screen sizes. -->Adaptations for users who prefer a dark color scheme.

## step 3:

In the body section, create a division with the text “Saveetha Engineering College”. Also in the body section, create a list with links to the SEC Home Page, My Camnu, and GitHub.

## step 4:

Close the HTML structure.

## CODE: 7 (i):
```
<!DOCTYPE html>
<html>
<head>
    <title>EX-07(i)</title>
    <style>
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

    </style>
</head>
<body>
  <div>
    SAVEETHA ENGINEERING COLLEGE
  </div>
    <ul>
        <li><a href="https://www.saveetha.ac.in/">SEC Home Page</a></li>
        <li><a href="http://lms.ai.saveetha.in/my/">moodle login page</a></li>
        <li><a href="https://www.github.com">GitHub</a></li>
    </ul>
  </body>
  </html>
```
## OUTPUT: 7(i):
![image](https://github.com/23008344/ODD2023-WT-Ex-07-CSS/assets/145742655/2436763b-c033-4cfc-84ea-20f3aab7fbf1)

![image](https://github.com/23008344/ODD2023-WT-Ex-07-CSS/assets/145742655/c5cc672e-7272-4b53-8719-22f868e578fe)

![image](https://github.com/23008344/ODD2023-WT-Ex-07-CSS/assets/145742655/e187fe57-dcc3-4c07-bc9f-71b3488783f9)


## Ex-07(ii)-CSS:

## AIM:
 
 To use a media query in CSS to apply different styles to a webpage for mobile devices (with widths less than 600px) and desktop devices (with widths greater than or equal to 600px) by providing an example CSS snippet to demonstrate your answer.

## DESIGN STEPS: 7(ii):

## step 1:
 
 Start the HTML document and create the root element.

## step 2:

Inside , create the element and include a style element for CSS rules.

## step 3:

Define CSS rules for desktop devices. Use a media query to define CSS rules for mobile devices.

## step 4:

Create the element inside , which will contain the webpage content.

## step 5:

Inside , create a

for the heading and an
for the list of hyperlinks.

## step 6:

End the HTML document by closing all open tags.

## CODE: 7(ii):

```
<!DOCTYPE html>
<html>
<head>
<style type="text/css">
    /* CSS rules for desktop devices */
    body {
        background-color: lightblue;
    }

    /* CSS rules for mobile devices */
    @media only screen and (max-width: 600px) {
        body {
            background-color: lightgreen;
        }
    }
</style>
</head>
<body>
    <div>
    SAVEETHA ENGINEERING COLLEGE
  </div>
    <ul>
        <li><a href="https://www.saveetha.ac.in/">SEC Home Page</a></li>
        <li><a href="http://lms.ai.saveetha.in/my/">moodle login page</a></li>
        <li><a href="https://www.github.com">GitHub</a></li>
  </body>
  </html>
```
## OUTPUT:7(ii):

![image](https://github.com/23008344/ODD2023-WT-Ex-07-CSS/assets/145742655/c7706eaf-5408-43f6-8039-b795ceadd1a9)

![image](https://github.com/23008344/ODD2023-WT-Ex-07-CSS/assets/145742655/e09fd2ef-0355-48d6-8c10-d5abf3a16630)


## Ex-07(iii)-CSS Orientation-based Media Query:

## AIM:

To explain how you can use CSS media queries to apply different styles based on the orientation (landscape or portrait) of the device. Provide a CSS example where you change the background color of the body based on the orientation.

## DESIGN STEPS:7(iii)

## Step 1:

Identify the section in your HTML file where you want to add the CSS. This is typically within the style tags in the section.

## Step 2:

Define a CSS media query for each orientation. The syntax for a media query is @media (orientation: value), where value can be either portrait or landscape.

## Step 3:

Within each media query, specify the CSS rules you want to apply. In this case, you want to change the background color of the body.

## Step 4:

Close the media query with a.

## Step 5:

Repeat steps 2-4 for the other orientation.

## Step 6:

Save your HTML file.

## Step 7:

Open your HTML file in a web browser and change the orientation of your device to see the different styles applied.

## CODE: 7(iii):

```
<!DOCTYPE html>
<html>
<head>
<style type="text/css">
    @media (orientation: portrait) {
        body {
            background-color: rgb(228, 236, 192);
        }
    }

    @media (orientation: landscape) {
        body {
            background-color: rgb(235, 144, 238);
        }
    }
</style>
</head>
<body>
    <div>
    SAVEETHA ENGINEERING COLLEGE
  </div>
    <ul>
        <li><a href="https://www.saveetha.ac.in/">SEC Home Page</a></li>
        <li><a href="http://lms.ai.saveetha.in/my/">moodle login page</a></li>
        <li><a href="https://www.github.com">GitHub</a></li>
  </body>
  </html>
```
## OUTPUT:7(iii):

![image](https://github.com/23008344/ODD2023-WT-Ex-07-CSS/assets/145742655/4a1ea4f6-3447-4529-a718-85730a5dc5aa)

![image](https://github.com/23008344/ODD2023-WT-Ex-07-CSS/assets/145742655/6639c32c-8981-40ec-aaae-f95bb779e8b3)


## Ex-07(iv)-CSS Responsive Typography:

## AIM:

To describe how you would use media queries to adjust typography (like font size and line spacing) on a website to improve readability across different device sizes, from mobile phones to large desktop monitors. Include a CSS code snippet in your explanation.

## DESIGN STEPS: 7(iv):

## Step 1:

Identify the HTML elements you want to style. In your case, it’s the div and li elements.

## Step 2:

Define the base styles for these elements. This will be the default styling that applies when no media queries match.

## Step 3:

Use media queries to apply different styles for different device sizes. The @media rule is used in CSS to apply styles for specific media types/devices.

## Step 4:

Inside the media queries, specify the device size for which the styles should apply. You can use min-width and max-width properties to target devices with widths within a certain range.

## Step 5:

Adjust Typography: Inside each media query block, adjust the typography (like font size and line spacing) for the identified elements.

## Step 6:

Test Your Styles.

## Step 7:

Iterate: Adjust your media queries and styles as needed based on your tests.

## CODE: 7(iv):

```
<!DOCTYPE html>
<html>
<head>
<style type="text/css">
    div, li {
        font-size: 16px;
        line-height: 1.5;
    }

    @media screen and (min-width: 600px) {
        div, li {
            font-size: 18px;
            line-height: 1.6;
        }
    }

    @media screen and (min-width: 900px) {
        div, li {
            font-size: 20px;
            line-height: 1.7;
        }
    }

    @media screen and (min-width: 1200px) {
        div, li {
            font-size: 22px;
            line-height: 1.8;
        }
    }
</style>
</head>
<body>
    <div>
        SAVEETHA ENGINEERING COLLEGE
  </div>
    <ul>
        <li><a href="https://www.saveetha.ac.in/">SEC Home Page</a></li>
        <li><a href="http://lms.ai.saveetha.in/my/">moodle login Page</a></li>
        <li><a href="https://www.github.com">GitHub</a></li>
  </body>
  </html>
```
## OUTPUT:7(iv):

![image](https://github.com/23008344/ODD2023-WT-Ex-07-CSS/assets/145742655/11b898f6-2f02-467c-b206-ff146f583bdc)

![image](https://github.com/23008344/ODD2023-WT-Ex-07-CSS/assets/145742655/b9f401b3-754a-4e2a-9724-7d299993d6b0)

![image](https://github.com/23008344/ODD2023-WT-Ex-07-CSS/assets/145742655/6a33e08e-f6fe-48d5-a842-848be98645e8)

## AIM:

To use a media query to change the styling of a webpage when it is printed, such as changing the background to white and hiding non-essential elements. Provide a CSS example.

## DESIGN STEPS: 7(v):

## Step 1:

Identify the HTML elements you want to style. In your case, it’s the div and li elements.

## Step 2:

Define the base styles for these elements. This will be the default styling that applies when no media queries match.

## Step 3:

Use media queries to apply different styles for different media types. The @media rule is used in CSS to apply styles for specific media types/devices.

## Step 4:

Inside the media queries, specify the media type for which the styles should apply. You can use print to target printers.

## Step 5:

Adjust Styles: Inside each media query block, adjust the styles for the identified elements. You can change the background to white and hide non-essential elements.

## Step 6:

Test your styles using the print preview feature in browsers to ensure they work as expected.

## Step 7:

Iterate: Adjust your media queries and styles as needed based on your tests.

## CODE: 7(v)

```
<!DOCTYPE html>
<html>
<head>
<style type="text/css">
    div, li {
        font-size: 16px;
        line-height: 1.5;
    }

    @media screen and (min-width: 600px) {
        div, li {
            font-size: 18px;
            line-height: 1.6;
        }
    }

    @media screen and (min-width: 900px) {
        div, li {
            font-size: 20px;
            line-height: 1.7;
        }
    }

    @media screen and (min-width: 1200px) {
        div, li {
            font-size: 22px;
            line-height: 1.8;
        }
    }
</style>
</head>
<body>
    <div>
        SAVEETHA ENGINEERING COLLEGE
  </div>
    <ul>
        <li><a href="https://www.saveetha.ac.in/">SEC Home Page</a></li>
        <li><a href="http://lms.ai.saveetha.in/my/">moodle login Page</a></li>
        <li><a href="https://www.github.com">GitHub</a></li>
  </body>
  </html>
```
## OUTPUT:7(v):

![image](https://github.com/23008344/ODD2023-WT-Ex-07-CSS/assets/145742655/131ba717-2788-4c9c-bf74-5143551a9b88)

![image](https://github.com/23008344/ODD2023-WT-Ex-07-CSS/assets/145742655/c1644cff-f1a8-4276-9c9c-d7f2e5673d67)


## Ex-07(vi)-Dark Mode Implementation:

## AIM:

With the increasing popularity of dark mode in user interfaces, explain how you would use a media query to detect if the user has set their system to prefer a dark color scheme. Provide an example of how you would change the background and text colors of a website based on this preference.

## DESIGN STEPS: 7(vi):
## Step 1:

Use the prefers-color-scheme media feature, which is used to detect if the user has requested the system use a light or dark color theme.

## Step 2:

The prefers-color-scheme media feature can have the values light, dark, or no-preference.

## Step 3:

In your CSS, you can use this feature within a @media rule to apply different styles depending on the user’s preference.

## Step 4:

You can set the background color to black and the text color to white when the user prefers a dark color scheme.

## Step 5:

Conversely, you can set the background color to white and the text color to black when the user prefers a light color scheme.

## Step 6:

If the user has no preference, you can choose a default color scheme.

## Step 7:

Remember to test your website in both light and dark modes to ensure the colors work well in both settings.

## CODE: 7(vi):

```
<!DOCTYPE html>
<html>
<head>
<style type="text/css">
    body {
        background-color: white;
        color: black;
    }
    @media (prefers-color-scheme: dark) {
        body {
            background-color: black;
            color: white;
        }
    }
    @media (prefers-color-scheme: light) {
        body {
            background-color: white;
            color: black;
        }
    }
</style>
</head>
<body>
    <div>
        SAVEETHA ENGINEERING COLLEGE
  </div>
    <ul>
        <li><a href="https://www.saveetha.ac.in/">SEC Home Page</a></li>
        <li><a href="http://lms.ai.saveetha.in/my/">moodle login page</a></li>
        <li><a href="https://www.github.com">GitHub</a></li>
  </body>
  </html>
```
## OUTPUT:7(vi):

![image](https://github.com/23008344/ODD2023-WT-Ex-07-CSS/assets/145742655/595f2793-d8bb-498e-af48-d48b514511b8)


![image](https://github.com/23008344/ODD2023-WT-Ex-07-CSS/assets/145742655/e6041c06-5e02-4e94-8ef3-9f161160c4f9)

