# Neural-Style-Transfer-Model
# 🖼️ Neural Style Transfer with TensorFlow

This project implements **Neural Style Transfer** using a custom pipeline in **TensorFlow 2**. It generates a new image that combines the **content of one image** with the **style of another**, producing visually appealing artistic results.


## 🧠 How It Works

1. **Load and preprocess** the content and style images
2. Use **VGG19** (pre-trained on ImageNet) to extract feature maps from specific layers
3. Compute:
   - **Content Loss** (difference in content features)
   - **Style Loss** using **Gram Matrices** (to capture textures and patterns)
4. Optimize the generated image using **Adam optimizer**
5. Save the final stylized image



