# EDSR-net
The implementation of EDSR network in different color spaces
In this work an EDSR network is implemented based on the article "Enhanced Deep Residual Networks for Single Image Super-Resolution" (https://arxiv.org/abs/1707.02921). It is implemented in 3 variations for RGB, XYZ and YCbCr color spaces. Timofty dataset is used as a train dataset, Set5 as a test dataset.
## Obtained results in different color spaces
| Color space           | SSIM  | PSNR   |
| ----------------------| ------| -------|
| RGB                   | 0.867 | 32.248 |
| XYZ                   | 0.835 | 31.311 |
| YCbCr                 | 0.863 | 31.580 |
| Bicubic interpolation | 0.860 | 31.958 |
For YCbCr color space I evaluate PSNR on the Y channel only due to article
