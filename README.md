# ashish-neural_style_transfer
for college project 
<br>
Author Ashish kumar,samriddh,harkirat (team work)
<br>

Project by Ashish Kumar

Registration Number: 21BCON434

📌 Introduction

Neural Style Transfer (NST) is a deep learning technique that applies the artistic style of one image to the content of another. This project leverages deep neural networks, specifically convolutional neural networks (CNNs), to blend content and style effectively.

🔍 Objective

The primary objective of this project is to develop a model that can generate artistic images by combining the style of a reference image with the content of another image using deep learning techniques.

🛠 Technology Stack

Programming Language: Python

Framework: TensorFlow, PyTorch

Development Platform: Google Colab

Libraries Used: OpenCV, Matplotlib, NumPy, PIL, SciPy


📂 Project Structure

📁 Neural_Style_Transfer
│── 📄 README.md
│── 📄 nst.ipynb (Google Colab Notebook)
│── 📂 images/
│   ├── content.jpg
│   ├── style.jpg
│   ├── output.jpg
│── 📄 requirements.txt

📜 Methodology

1. Load Content and Style Images

Use OpenCV or PIL to read and preprocess images.



2. Feature Extraction Using Pre-trained CNNs

Utilize a pre-trained VGG19 model to extract content and style features.



3. Compute Loss Functions

Content Loss: Measures how much the generated image deviates from the content image.

Style Loss: Compares the Gram matrices of style features to ensure style consistency.

Total Variation Loss: Helps in reducing noise and improving smoothness.



4. Optimize the Generated Image

Use gradient descent and backpropagation to iteratively update the image.



5. Generate Final Stylized Image

Save and visualize the output image.




📌 Results

The model successfully transfers the artistic style of a painting to a real-world image while preserving its content structure. The generated images exhibit a blend of colors and patterns inspired by the style image.

📑 Future Improvements

Improve computational efficiency using style transfer acceleration techniques.

Implement real-time style transfer using lightweight neural networks.

Extend the model to video style transfer applications.


📎 References

Gatys, L.A., Ecker, A.S., & Bethge, M. (2015). "A Neural Algorithm of Artistic Style"

TensorFlow & PyTorch Documentation
