# 🎨 Colorize Black & White Images using Deep Learning

This project demonstrates how to colorize grayscale (black & white) images using a pre-trained Deep Learning model with OpenCV.

The model predicts the color information for an input image by estimating the **a** and **b** channels of the Lab color space while using the **L (lightness)** channel from the grayscale image.

---

## 📌 Project Overview

Image colorization is the process of converting a grayscale image into a colored image.

In this project:

- A black & white image is provided as input
- The Deep Learning model predicts color components
- A colorized version of the image is generated as output

---

## 🧠 Technologies Used

- Python
- OpenCV (cv2)
- NumPy
- Matplotlib


---

## ⚙️ Model Details

The project uses a **pre-trained Caffe model** trained on the ImageNet dataset.

Required files:

- `colorization_deploy_v2.prototxt`
- `colorization_release_v2.caffemodel`
- `pts_in_hull.npy`

---

## 🚀 How It Works

1. Load a grayscale image
2. Convert image to Lab color space
3. Extract the L channel
4. Feed L channel to the neural network
5. Predict a & b channels
6. Combine L + predicted ab channels
7. Convert back to RGB/BGR

---

## 🖼️ Features

✔ Colorizes black & white images  
✔ Uses Deep Learning (no manual coloring)  
✔ Simple Python implementation  
✔ Optional GUI for interaction  

---


