---
toc: true
layout: post
title: PBL Project Addition
---

# Before Adding Greyscale 

![]({{site.baseurl}}/images/before.png)

# After Adding Greyscale 

![]({{site.baseurl}}/images/after.png)

# Code

![]({{site.baseurl}}/images/a.png)
![]({{site.baseurl}}/images/b.png)

- The HTML file defines a canvas element and an input element of type "file" for selecting an image file.

- The CSS file adds a border to the canvas element.

- The JavaScript code sets up event listeners for the input element and the canvas element.

- When a file is selected, the handleImage() function is called. This function loads the image file using the FileReader object and creates a new Image object.

- Once the image is loaded, the function scales it down to a maximum size of 300x250 pixels (using the maxWidth and maxHeight variables), and draws the original image onto the canvas using the drawImage() method.

- The getImageData() method is then used to get the image data from the canvas. This method returns an ImageData object containing a one-dimensional array of pixel data.

- The code loops through each pixel in the array and calculates its grayscale equivalent using the formula 0.2989 * red + 0.5870 * green + 0.1140 * blue. The resulting grayscale value is then assigned to the red, green, and blue values for that pixel.

- Finally, the putImageData() method is used to put the modified image data back onto the canvas, effectively rendering the grayscale version of the image.