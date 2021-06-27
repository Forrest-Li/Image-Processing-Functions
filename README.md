## Image Processing Functions

### Introduction

* Programmatically coded some OpenCV functions in Python
* Functions including:
   1. Image scaling: Downscaling and upscaling provided, floating point scaling ratio allowed
   2. Blurring/Denoising: Average blurring, Medium blurring and Gaussian blurring methods provided
   3. Bonus: with provided signature image, processed image can be signed(overlaid) with personal image

### Calling functions

* Image scaling: `resize_main()`
   * processed images will be shown below
   * Input instructions:
```
Resize ratio (height,width): 
Example: 0.3,1.5
> <input_size_1>,<input_size_2>
```

* Blurring/Denoising：`blur_main()`
   * 3 blurring methods will all be applied
   * processed images will be shown below
  
### Future update

* Convert Jupyter Notebook structured program to Python files based
* Integrate more OpenCV image processing functions like rotation, morphological methods(erosion, dilation, edges detection, and etc.), and etc.
