# PRODIGY_GA_04

## Image-to-Image Translation using Pix2Pix (cGAN)

### Objective
Implement an Image-to-Image Translation model using a Conditional GAN (Pix2Pix) to generate realistic images from input images.

### Technologies Used
- Python
- PyTorch
- Pix2Pix (Conditional GAN)
- Google Colab

### Dataset
Pix2Pix Facades Dataset

### Steps Performed
- Installed required libraries
- Cloned the official Pix2Pix repository
- Downloaded the pretrained Pix2Pix model
- Downloaded the Facades dataset
- Generated translated images using the pretrained model
- Compared the input image, generated image, and ground truth image

### Output
The model successfully translated facade label images into realistic building images.

### Folder Structure

PRODIGY_GA_04/
│── Prodigy_GA_04.ipynb
│── README.md
│── requirements.txt
│── outputs/
│ ├── 100_real_A.png
│ ├── 100_fake_B.png
│ └── 100_real_B.png

### Conclusion
This project demonstrates Image-to-Image Translation using a Conditional GAN (Pix2Pix). The pretrained model successfully generated realistic facade images from label maps.