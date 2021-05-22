## Welcome to SKetchFabShowAndHide 

# Custom viewer for Sketfab utilizing the Viewer API to allow showing and hiding of the model's parts

Example Running Here: https://croisened.github.io/SketchFabShowAndHide/?id=784e95f4f22545199be7e165af6437f8


To use this project you only need 3 files...

- index.html (This file just has the HTML scaffolding to house the Sketchfab API viewer)
- style.css (This file contains the bootstrap based layout information)
- sf_showhide.js (This file contains all the code to initialize the Sketchfab viewer, process all the Matrix Transforms and ultimatley generate the treeview with show and hide buttons for each object in the scene)

In the javascript file there is an "id" variable that you can change to be any model on Sketchfab based on that model's guid you can see in the URL for any given model.  This acts as default model to load in the event there is no "id" variable set in the querystring for the HTML page so you can simply chage it there as well to view any model you choose.





### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

