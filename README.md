# Cell-Nuclei-Segmentation-from-Histology-images-using-Conditional-Generative-Adversarial-Network-Pytorch-Implementation
## Overview
### Data
In order to directly process the image, the histology images and corresponding segmentation maps are merged as shown below.

![alt text](https://github.com/babajide07/Cell-Nuclei-Segmentation-from-Histology-images-using-Conditional-Generative-Adversarial-Network-/blob/master/Results/gan_image.png)

## Results
### Qualitative
![alt text](https://github.com/babajide07/Cell-Nuclei-Segmentation-from-Histology-images-using-Conditional-Generative-Adversarial-Network-/blob/master/Results/results.png)

### Quantitative 
| Model  | Dice Measure |
| ------------- | ------------- |
| Unet with no data augmentation (Baseline) | 0.637  |
|  Unet with data augmentation  | 0.693  |
|  cGAN with data augmentation  | 0.723  |

