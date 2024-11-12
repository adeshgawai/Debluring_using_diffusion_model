# Motion Deblurring using Diffusion Model

This repository contains the implementation of a motion deblurring model using a *Diffusion-based approach. The primary goal of this project is to enhance image clarity by removing motion blur caused by camera shake, fast-moving objects, or environmental factors. The model is trained on the **GoPro Dataset* and uses advanced deep learning techniques to recover sharp details from motion-blurred images.

## Objective

- Apply a diffusion-based model to effectively address motion blur in images.
- Improve the speed and quality of image deblurring.
- Achieve high fidelity to the original image while reducing artifacts.

## Installation

To set up this project, you need the following dependencies:

- *Python 3.9*  
- *PyTorch 2.0.0*  
- *NVIDIA GPU + CUDA* (for faster computation)

### Steps to Install:

1. Create and activate a new *conda environment*:
   ```bah
   !git clone https://github.com/rohitrrg/image_editing.git
   !cd image_editing
   !conda create -n hi_diff python=3.9
   !conda activate hi_diff
   !pip install -r requirements.txt
   ```

### Dataset

This project uses the **GoPro Dataset** for training the deblurring model.

You can download the dataset from : [Google Drive](https://drive.google.com/file/d/1KYmgaQj0LWSCL6ygtXcuBZ6DfJgO09RQ/view?usp=drive_link)

# image_editing
### Training
![Screenshot from 2024-11-11 06-36-21](https://github.com/user-attachments/assets/0a16d6ec-8b9f-4df0-9d1d-ab5ab343bc25) ![Screenshot from 2024-11-11 06-36-53](https://github.com/user-attachments/assets/80d3451d-acad-42c9-8fc6-1791cede9118)

### Evaluate
![Screenshot from 2024-11-10 23-45-27](https://github.com/user-attachments/assets/6fab7cb5-6ffe-4a02-88c7-9dd368b2fd86)

### Test on Images
![image](https://github.com/user-attachments/assets/bc0ae3db-a0ff-498f-b31e-06b656c8f467)

![image](https://github.com/user-attachments/assets/dcd4f566-e7c9-4b6d-a32d-b0f20a9460b5)

![image](https://github.com/user-attachments/assets/75052396-c041-4637-8efa-69367ca648e1)

![GOPR0410_11_00-000136](https://github.com/user-attachments/assets/01103d96-58d0-4dd7-ab56-276366427910)
