# Chest X-Ray Image Super-Resolution

## Code Overview

The provided Python script implements Chest X-Ray image super-resolution using the Enhanced Super-Resolution Convolutional Network (ESPCN). The script utilizes TensorFlow and Keras for model development, training, and evaluation. The ESPCN introduces a sub-pixel convolution layer, optimizing upscaling filters for enhanced image resolution.

### Prerequisites

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib
- PIL (Pillow)

### Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/chest-xray-super-resolution.git
   cd chest-xray-super-resolution

2. Install dependencies:

   ```bash
   Copy code
   pip install -r requirements.txt


3. Mount Google Drive (if using Colab):

   from google.colab import drive
   drive.mount('/content/drive')
   
4. Define dataset path and configure parameters:

   root_dir = '/content/drive/MyDrive/image_superresolution_data'
   crop_size = 300
   upscale_factor = 3
   batch_size = 8
   epochs = 100

5. Run the main script:

   python image_superresolution.py
