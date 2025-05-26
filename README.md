# Multi-Feature Analysis for Source Camera Identification
This study focuses on source camera identification using image-based forensic techniques to address the growing concerns of digital image manipulation. </br>
The objective is to reliably trace an image back to its originating device using four analytical methods: Photo-Response Non-Uniformity (PRNU), Color Filter Array (CFA) pattern estimation, color consistency analysis, and camera calibration assessment. Images captured using different smartphones, specifically iPhone and Samsung models, were used as the dataset. </br>

1. PRNU analysis was applied to extract sensor-specific noise patterns.
2. CFA analysis estimated the underlying color layout of the camera sensor.
3. Color consistency checked the mean and variation of RGB channel values.
4. Camera calibration assessed the white balance behavior through relative RGB ratios. </br>

The system used statistical comparisons such as Mean Squared Error (MSE), Structural Similarity Index (SSIM), and Pearson Correlation Coefficient to compare PRNU patterns, and mean/standard deviation calculations for color and calibration analysis. </br>

The results showed significant differences between the devices: PRNU patterns were unique to each camera, CFA patterns indicated iPhone dominance in red channel (R > B > G) and Samsung in blue (B > R > G), while white balance estimation revealed consistent calibration biases—iPhone images leaned toward warmer tones, and Samsung toward cooler ones. 
These device-specific features enabled accurate differentiation between camera sources. The integration of all four methods provided a robust framework for identifying the source of a digital image using only the image data itself. </br>

This research enhances digital forensics by demonstrating that even seemingly similar photos from different phones carry hidden, measurable traces of their origin. The approach is non-intrusive, device-agnostic, and applicable in legal, forensic, and cybersecurity investigations. Overall, the study confirms that combining PRNU, CFA, color consistency, and calibration is a powerful method for authenticating image sources with high reliability.
