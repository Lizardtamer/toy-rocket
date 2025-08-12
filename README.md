# Inline vs Style Elements vs Link Elements

## Assignment: Decorating a Space Rocket Page

In this fun and creative assignment, you will work on styling a webpage that showcases a Space Rocket toy.

<div style="display: flex; flex-direction: column; justify-content: center;  align-items: center;
">
  <div style="display: flex; ">
    <img src="./Example/rocket-inline.png" width="300" style="margin-right: 1%; margin-top: 1%"/> 
    <img src="./Example/rocket-style.png" width="300" style="margin-left: 1%; margin-top: 1%" />
  </div>
</div>

### Instructions

**Part 1: Inline Styling (`rocket-inline.html`)**

1. Render a divider element `<div>` to hold information about the toy
   - Render the header "Space Rocket Adventure!" inside the div
   - Render the image of the toy (RocketToy.jpg) inside the div
  
2. Use inline styling to:
   - Change the background color of the `<div>` to sky blue.
   - Change the text color to bright yellow.
   - Move the header to the horizontal center of the page
   - Move the image to the horizontal center of the page 


**Part 2: Style Elements (`rocket-style.html`)**

1. Render a divider element `<div>` to hold information about the toy
   - Render the header "Space Rocket Adventure!" inside the div
   - Render the image of the toy (RocketToy.jpg) inside the div
  
2. Add a style element `<style>` at the top of the page.
    - Define a style-block for a class called "rocket-div"
        - Inside the style-block, set the background color to midnight blue.
        - Inside the style-block, set the text color to silver.
        - Move the header to the horizontal center of the page.
        - Move the image to the horizontal center of the page.
    - Assign the div element to the rocket-div class

Take a look at the Example folder for an idea of how the end result should look.