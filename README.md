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

## 📜 Code License

The code in this repository is licensed under the [MIT License](LICENSE).  
Feel free to use, modify, and distribute it freely under the terms of the MIT License.

## 🤖 Trained Models License

The trained models included in the `trained_models/` folder were created using a dataset licensed under  
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Therefore, the models themselves are also distributed under the same license.  
Please use them only for non-commercial purposes and provide appropriate attribution.

If you plan to use the models commercially or redistribute them, please consult the original dataset license terms and seek permission.

## 🖼️ Results License

The generated images and other results provided in the `results/` folder  
are considered derivative works based on the dataset licensed under  
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Therefore, these results are also distributed under the same license.  
Please use and share them only for non-commercial purposes with appropriate attribution.

