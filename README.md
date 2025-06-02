# DCGAN Art Image Generator

This project implements a simple Deep Convolutional Generative Adversarial Network (DCGAN) to generate art images of size 64x64 pixels. The notebook covers data loading, model definition, training, and image generation.

## 🖼️ Dataset

The dataset used in this project comes from [Kaggle](https://www.kaggle.com/datasets/sankarmechengg/art-images-clear-and-distorted) and was originally created by Sankar Balasubramanian (sankarmechengg) and originally contains 512x512 pixel images of artworks.

For training with DCGAN:

Only clear images were used

Images were resized to 64x64 pixels

Horizontal flip augmentation was applied

Note: The dataset is not included in this repository. You’ll need to download it manually from Kaggle.

### 📜 License

This project dataset is licensed under the  
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Please refer to the original dataset source and license for usage terms.

## 🔧 Project Structure

- `Generating_Art_Images_DCGAN.ipynb`  
	Main Jupyter notebook containing data loading, model definitions, training process, and image generation.
  
- `trained models\`
	Contains .pth files with trained weights for the generator and discriminator.

- `results\`
	Includes: .png images comparing real vs. fake samples. A .gif showing a smooth latent space interpolation, a looped animation of images generated 	 by the trained model while walking through the latent vector space.

## Requirements

- 🐍 Python 3.x

- 🔥 PyTorch

- 📦 torchvision

- 📊 matplotlib

- 🎞️ imageio

## 🛠️ Usage

1. Open the Generating_Art_Images_DCGAN.ipynb notebook.

2. Run cells sequentially to download data, define models, train, and generate images.

3. GPU is recommended for faster training.

