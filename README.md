# 🖼️ Neural Style Transfer with TensorFlow

This project implements **Neural Style Transfer** using a custom TensorFlow pipeline. It blends the **content** of one image with the **style** of another, generating a beautiful, stylized output. The model uses a pre-trained **VGG19** network to extract features and optimize a new image that captures the desired content and artistic style.

---

## 💡 Features

- ✅ Custom implementation of Neural Style Transfer
- ✅ Uses **VGG19** for feature extraction
- ✅ Style and content loss based training
- ✅ Supports any combination of content & style images
- ✅ Final stylized image is saved for future use

---

## 🛠️ Technologies Used

- Python
- TensorFlow 2.x
- NumPy
- PIL (Pillow)
- Matplotlib

---

## 🧠 How It Works

1. **Load and preprocess** the content and style images
2. **Extract feature representations** using VGG19
3. **Define and compute losses**:
   - Content loss
   - Style loss (using Gram matrix)
4. **Optimize** the generated image using gradient descent
5. **Save** the stylized output image

---

## 📦 Output

- Final stylized image saved as `customized_image.jpg`
- Easy to reuse the pipeline with different content/style images





