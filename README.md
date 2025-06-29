# ISRO Hackathon

## Problem Statement-12
Dual Image Super Resolution for High-Resolution Optical Satellite Imagery and its Blind Evaluation

Acquiring high-resolution data from satellite platforms is an expensive operation due to resource constraints. Hence, satellites acquire multiple low-resolution images often shifted by half a pixel in both along and across track directions. These low-resolution images are utilized to generate high-resolution images. The quality of high-resolution images often depends on various satellite system parameters including the algorithm used for super-resolving. However, assessing the quality of these generated super-resolved images is challenging due to the absence of ground-truth references. This also necessitates the use of blind (no-reference) quality assessment techniques that can evaluate both the perceptual realism and fidelity of super-resolved images.

## Objective
- To generate high-resolution images from two (dual) low-resolution images.
- To evaluate the image quality using both predefined metrics and blind visual quality assessment techniques in the absence of ground-truth references.

## Expected Outcomes
- Super-resolved image exceeding the resolution of low-resolution inputs.
- Quality evaluation metric under blind visual assessment settings.

## Dataset Required
- Low-resolution satellite images as input.
- High-resolution satellite image for evaluation purpose (if available).

## Suggested Tools/Technologies
- Both classical and deep learning-based techniques can be considered.

## Expected Solution / Steps to be followed to achieve the objectives
### Classical Techniques
- Estimation and application of degradation functions from low-resolution images.
- Registration of images.
- Non-uniform interpolation.

### Deep Learning Techniques
- Data pipeline setup for training.
- Model selection and fine-tuning.
- Evaluation on validation data.

### Blind Assessment Techniques
- Generate ground-truth (GT) quality score under reduced reference setting from super-resolved images using state-of-the-art metrics.
- Methodology selection: handcrafted features ML-based or deep feature-based quality scoring.
- Correlation (Rank/Value) of predicted scores with GT scores and sensitivity analysis across quality levels.

## Evaluation Parameters
- Full-reference metrics: MSE, RMSE, SSIM, PSNR (where applicable).
- Correlation of blind assessment results with full-reference metrics.
- Robustness of blind metrics under different levels of image quality.

## Image Representing Problem Statement

> _Note: The approach is not stated yet. This is just an initialization of the project repository with data and notebook._ 