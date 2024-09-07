This project is a simple recreation of a Rothko-style painting using HTML and CSS. The goal was to simulate the abstract, color-block paintings of artist Mark Rothko, focusing on large areas of color, subtle gradients, and slight rotations to give an organic, hand-painted feel.

Project Structure
Files Included:
index.html: Contains the HTML structure of the page.
styles.css: Contains all the CSS styles used to create the painting and layout.
HTML Breakdown:
The HTML file is structured with a simple div hierarchy:
<div class="frame">: Simulates a frame around the painting.
<div class="canvas">: Represents the canvas where the painting elements are located.
<div class="one">: The first color block (top rectangle).
<div class="two">: The second color block (middle rectangle).
<div class="three">: The third color block (bottom rectangle).
CSS Highlights:
.frame: Acts as a thick border around the painting to give the impression of a framed artwork.
.canvas: A container holding the colored blocks, with a blurred effect to soften the transitions between blocks.
Color Blocks:
.one, .two, .three: Each div represents a color block with slight rotation and box shadows to simulate depth. Each block uses specific colors that are somewhat reflective of Rothko’s signature style.
Blur effects: These are added to give the abstract, dream-like quality of Rothko’s paintings.
Visual Design:
Frame: A thick black border is used to simulate a gallery frame around the canvas.
Colors: Warm and earthy tones are chosen to echo the aesthetic of Rothko’s abstract color fields.
Subtle Rotation & Shadowing: To mimic the imperfections of hand-painting, each color block is slightly rotated with soft shadows applied.
Blur Effect: The filter: blur() CSS property is used to give a slight out-of-focus effect to the color blocks, adding a feeling of depth and abstraction.
How to Use:
Clone or download this repository to your local machine.
Open the index.html file in any modern web browser.
The painting will be displayed with a simulated frame and abstract, color-blocked elements.
Future Enhancements:
Add interactivity using JavaScript (e.g., dynamic color changes or animations).
Optimize for different screen sizes using responsive design techniques.
Explore using CSS animations to gradually reveal the painting or simulate brush strokes.
Inspiration:
This project was inspired by the work of Mark Rothko, a prominent 20th-century abstract painter known for his large color field paintings. The project seeks to explore how simple HTML and CSS techniques can be used to recreate abstract art styles.

![Rothko painting](https://github.com/user-attachments/assets/08f8b5eb-4494-48bd-99af-066497a86392)
