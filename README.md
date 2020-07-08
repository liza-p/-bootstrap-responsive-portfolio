# bootstrap-responsive-portfolio

## Link
- URL to the deployed application 

[Portfolio](https://liza-p.github.io/responsive-portfolio/.)
## About
This website was built using Bootstrap CSS framework implementing responsive web design techniques.

## What does responsive design mean?
Responsive design is a way to put together a website so that it automatically scales its content and elements to match the screen size on which it is viewed. It keeps images from being larger than the screen width, and prevents visitors on mobile devices from needing to do extra work to read the website content.

The goal of responsive design is to avoid the unnecessary resizing, scrolling, zooming, or panning that occurs with sites that have not been optimized for different devices.

![](img/responsiveDesign.gif)

## Viewport
Pages optimized for a variety of devices must include a meta viewport tag in the head of the document. A meta viewport tag gives the browser instructions on how to control the page's dimensions and scaling.
```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  </head>
  ...
```

## Bootstrap Grid System
Bootstrap’s grid system uses a series of containers, rows, and columns to layout and align content. It’s built with flexbox and is fully responsive. Below is an example and an in-depth look at how the grid comes together.
```html
<div class="container"> 
    <div class="row">
    <div class="col-12 col-sm-6 my-3">
        <div class="image-wrapper">
        <img src="..." alt="cat" width="100%"/>
        <div class="text-block text-center py-2">
          <h4>...</h4>
        </div>
        </div>            
    </div>
```
## Previewing locally
This is a static website that can be viewed locally - just open the `index.html` file located in the main folder using any browser.

## Deploying
This website is deployed using GitHub pages. Any changes pushed to master will be
automatically deployed to the live application URL mentioned above.