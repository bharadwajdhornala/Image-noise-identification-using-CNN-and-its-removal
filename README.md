# Image-noise-identification-using-CNN-and-its-removal
Noise is any unwanted information added to the image when transmitted through any digital media. It is the result of errors in the image acquisition process that result in pixel values that do not reflect the true intensities of the real scene.

These noises are added due to faulty memory location, post-filtering, compression, weak focal length and other adverse conditions that may be present in the atmosphere or from image capturing gadgets.

Various types of noises such as Salt and Pepper noise, Gaussian noise, Poisson noise, Speckle noise, and many other fundamental noise types can cause degradation to the quality of an image. 

Prior to de-noising step, the image should be tested for the identification of noise because once the presence of noise is identified from the given image, a filter can be used to de-noise it.

# Denoising Filters
Standard Median Filter –
Replaces the center value of the sliding window with median of all other values in sliding window.
                             
Weighted Median Filter –
The operations involved in WMF are like SMF, except that WMF has weight associated with each of its filter element. 
                                   
# Evaluation Parameters
PEAK SIGNAL TO NOISE RATIO (PSNR):
          The higher the PSNR, the better the quality of the compressed, or reconstructed image.              
          Formula for calculating PSNR-    PSNR = 10 * log10(R^2 / MSE)
					
MEAN SQUARED ERROR (MSE):
          MSE represents the cumulative squared error between the compressed and the original image, whereas PSNR represents a measure of the peak error.The lower the value of MSE, the lower the error.
	  
	  






