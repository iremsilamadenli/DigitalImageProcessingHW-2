# DigitalImageProcessingHW-2
 Butterworth filter, Correlation , Zero-mean Correlation, Sum of Squared Difference , Normalized Cross Correlation... You can run directly on Google Colab. Outputs are available in files. It changes if you change your image.

<h2> 🚀 Task 1 A Results </h2>
<p align="left">
 
 The sum of squared difference (SSD) dissimilarity measure successfully matches the template to the target item in the picture, according to the findings of the template matching algorithm using various similarity measures. The output graphic, which displays a bounding box formed around the object of interest, makes this clear.
 
 However, in this instance, neither the normalized cross-correlation similarity measure nor the correlation similarity measure offers accurate matches. This is since these measurements are sensitive to changes in the image's brightness and contrast. The matching won't be precise if the object of interest's brightness and contrast are different from those of the template.
Lastly, the zero-mean correlation similarity measure is likewise unreliable in this situation. This is due to the fact that this measure normalizes the values of the pixels in the image, which may cause the loss of crucial details about the item of interest.
 
 In the end, the precise qualities of the photos being utilized determine the similarity measure that should be used for template matching. While the correlation and normalized cross- correlation measures are better suitable for photos when the item of interest has similar brightness and contrast to the template, the SSD dissimilarity metric is a solid option when there is substantial contrast between the object and the backdrop.
 
 
 
 <h2> 🚀 Task 1 B Results </h2>
<p align="left">
 
Since the zero-mean correlation similarity measure is less susceptible to brightness variations, the primary object is still reliably detected. The normalized cross-correlation similarity measure yields the most accurate result since it is resistant to brightness and scale variations. The sum of squared difference dissimilarity metric works well in this context since it is sensitive to texture and contrast variations.
 
 
 <h2> 🚀 Task 2 Results </h2>
<p align="left">
 
The Butterworth filter's form is determined by the value n. The pass to stop band transition steepens with increasing n, producing a stronger cut-off in the frequency domain. This can be seen in the filtering results, where the low pass filter with n=2 preserves more picture features than n=15.
 
ii. The Butterworth filter's cut-off frequency is controlled by the parameter D0. Larger pass bands and more high frequency noise are kept in the filtered picture with a smaller value of D0. A narrower pass band and higher high frequency noise suppression are produced by a bigger value of D0. It is clear from the filter-ring findings that the low pass filter with D0=60 preserves more picture information than the filter with D0=20.
 
The Gibbs phenomena, sometimes referred to as the ringing effect, is seen as oscillations in the filtered picture at edges with a lot of contrast. The Butterworth filter's abrupt cut-off results in this effect, which is visible in the high pass filter's accentuated edges. However, the flattening of the high frequency components in the low pass filter results prevents the ringing effect from being seen.
