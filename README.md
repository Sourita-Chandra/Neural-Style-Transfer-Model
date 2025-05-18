# Neural-Style-Transfer-Model
This project implements Neural Style Transfer using a custom TensorFlow pipeline.
It blends the content of one image with the style of another, generating a beautiful, stylized output. The model uses a pre-trained VGG19 network to extract features and optimize a new image that captures the desired content and artistic style.
\n
💡 Features
Custom implementation of Neural Style Transfer
Uses VGG19 for feature extraction
Style and content loss based training
Supports any combination of content & style images
Final stylized image is saved for future use
🛠️ Technologies Used
Python
TensorFlow 2.x
NumPy
PIL (Pillow)
Matplotlib
🧠 How It Works
Load and preprocess the content and style images
Extract feature representations using VGG19
Define and compute content/style losses
Use gradient descent to update the generated image
Save the stylized output image
📦 Output
Stylized image saved as stylized_output.jpg
Easy to reuse with different content/style combinations

