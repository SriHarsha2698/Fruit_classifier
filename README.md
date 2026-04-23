# Fruit_classifier
# Smart Self-Checkout Produce Recognition using Computer Vision

## Overview

This project demonstrates how computer vision can automate fresh produce recognition at supermarket self-checkout systems.

Customers often manually search for loose produce items such as bananas, apples, or oranges. This prototype uses deep learning to identify produce automatically, reducing checkout friction and improving customer experience.

---

## Business Use Case

Retailers such as Tesco can use this system to:

* Reduce self-checkout lookup time
* Improve customer experience
* Reduce scanning friction
* Support cashierless retail innovation

---

## Dataset

Custom fruit image dataset containing 9 classes:

* Apple
* Banana
* Cherry
* Chickoo
* Grapes
* Kiwi
* Mango
* Orange
* Strawberry

Approx. 40 images per class.

---

## Model

Transfer Learning using ResNet18 with PyTorch.

Applied image augmentation:

* Rotation
* Horizontal Flip
* Brightness Shift

---

## Results

* Test Accuracy: **84.4%**
* Strong performance across all classes
* Misclassifications mainly among visually similar fruits

---

## Example Output

Detected: Banana
Confidence: 96%
Price: £0.22

---

## Tech Stack

* Python
* PyTorch
* Torchvision
* Matplotlib
* Scikit-learn
* Google Colab

---

## Future Improvements

* Real-time webcam checkout
* Barcode + basket total
* Object detection for multiple items
* Deployment using Streamlit

---

## Author

Your Name
