# Image_Generator

Description:
The code takes a product image identifies the background space and then makes the background transparent. Now the product image is vectorized this way. To add a background, a new background image is blended with the vectorized image. During blending proper blurring effects are adjusted to ensure that edges are not sharp and discriminative. A mirror-reflection effect is then created on this output image. This is done by creating a gradient and then applying this gradient to the flipped output image. Finally, the flipped output image is stacked below the original output with a cropped height to create a partial mirror or water-like reflection. Open CV is the hero is this project.

To run the code:
1. download the ipynb file.
2. put the product in the same location as that of the code
3. run all the cells sequentially.
You can rename the files as taken in the code.
