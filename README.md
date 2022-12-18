# portrait-from-dice
A python script to convert an image to another image made entirely of 6-sided dice

Given an image file (PNG, JPG, JPEG), this program should perform the following operations:
1. Convert the image to grayscale (black and white)
2. Reacreate the image using as many 6-sided dice as possible
3. Toggle between a black background with white dice number or a white background with black numbers
4. Calculate the cost of creating such an image using 6-sided dice in dollars
5. Set a limit on how big the picture generated should be. Larger pictures would incur much more memory

## How to run the program
```makefile
make run <path-to-image>
```

The `path-to-image` parameter should specify the path to the PNG, JPG or JPEG image. 

