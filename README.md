Hosted link of project - https://shweta-sharma-1009.github.io/Animation-/

![Screenshot (363)](https://github.com/shweta-sharma-1009/Animation-/assets/128416925/7a99a9c1-7d21-459c-8fbf-87ae3a915358)
![Screenshot (364)](https://github.com/shweta-sharma-1009/Animation-/assets/128416925/fee8fd31-035d-4c4a-ac3e-1da77c669962)

Description -
HTML - 

This code is like the blueprint for a web page. Let's break it down:
<!DOCTYPE html>: This tells the browser that the code is written in HTML5, the latest version of HTML.
<html lang="en">: This is the starting tag for your HTML code, and it indicates that the language of your content is English.
<head>: This section contains important information about your webpage, like its title and how it should be displayed.
<meta charset="UTF-8">: This specifies the character encoding, which ensures your text appears correctly.
<meta http-equiv="X-UA-Compatible" content="IE=edge">: This helps the browser understand how to handle the webpage, especially for Internet Explorer.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: This sets how your webpage should appear on different devices.
<title>Document</title>: This is the title that appears in the browser's tab when your webpage is open.
<style>: Here, you can write CSS code to make your webpage visually appealing. CSS is used for styling, like colors and layouts.
<body>: This is where you put the main content of your webpage that people will see.
<!-- ... -->: These are comments that you can use to leave notes for yourself or others. They don't affect how the webpage looks.

CSS -
This code is used to create a visually appealing effect for images on a webpage. Let's break it down step by step:

Initial Setup: The first part, *{...}, sets some basic styling rules for all elements on the webpage. 
It makes sure that everything has no extra space around them and their size is calculated in a specific way.

Body Styling: The body{...} part is about how the main content of the webpage (like text and images) will be arranged.
It centers everything both horizontally and vertically on the page. The background color is set to black (#000), giving a dark background. The min-height: 100vh; ensures that the content takes up at least the full height of the visible screen.

Container Layout: The .container{...} part sets up a section to hold the images. 
It's made to be a flexible box that arranges its content evenly with space between them. The -webkit-box-reflect creates a subtle gradient reflection effect below the container.

Image Styling: The .container img{...} part is for styling the images inside the container. 
It limits their maximum width to 350 pixels, gives them a slight tilt and shadow to make them look 3D. They also have rounded corners.

Hover Effects: When you hover your mouse over the .container area, the images become a bit transparent (opacity: 0.3;). This creates a fading effect when you move your mouse over them.

Individual Image Hover: Additionally, when you hover your mouse over an individual image inside the container, that image smoothly turns back to its original angle (0 degrees) and becomes fully opaque again (opacity: 1;). This gives a more pronounced 3D-like effect.

In simple terms, this code makes a collection of images on a webpage appear like they're slightly tilted and three-dimensional. When you hover your mouse over the images, they react by becoming transparent and more pronouncedly 3D. It's a neat visual effect to enhance the user's interaction with the images.
