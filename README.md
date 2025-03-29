# project-1_Deepfake-facial-image-detection

# DeepFake Image Detection

## Problem Statement
With the rise of Generative Adversarial Networks (GANs) and other deep learning-based DeepFake techniques, ensuring the authenticity of online images and videos has become a significant challenge. The widespread use of DeepFake technology poses threats to privacy, media integrity, and trust in digital content. This project aims to build a deep learning-based model to effectively classify real and fake images using convolutional neural networks (CNNs). Our approach involves training multiple models and evaluating their performance in distinguishing DeepFake images from real ones.

## Approach
We implemented and compared the following deep learning architectures for DeepFake image detection:
- **ResNet**
- **DenseNet-121**
- **Custom CNN Architectures**


## Future Work
Future enhancements to this project include:
- Implementing **unsupervised clustering methods (e.g., autoencoders)** to explore natural groupings in real vs. fake images.
- Improving **model interpretability** using CNN visualization techniques.
- Enhancing robustness with **adversarial training** to detect more sophisticated DeepFake manipulations.

## Dataset Source
We used two publicly available datasets from Kaggle, combined for training and evaluation:
- [140K Real and Fake Faces](https://www.kaggle.com/xhlulu/140k-real-and-fake-faces)
- [Real and Fake Face Detection](https://www.kaggle.com/ciplab/real-and-fake-face-detection)

### Dataset Preparation
1. Download the datasets from the links above.
2. Create a folder named `combined-real-and-fake-faces/combined-real-vs-fake`.
3. Inside this folder, create three subfolders: `train`, `valid`, and `test`.
4. Merge the second dataset with the first and distribute images into the respective subfolders.

## Performance Metrics & Results
A detailed analysis of model performance, including accuracy, precision, recall, F1-score, and confusion matrices, is available in the full report.

## Conclusion
This project demonstrates the effectiveness of deep learning models in detecting DeepFake images. By leveraging CNNs, PCA, and SVMs, we successfully classified real and fake images with high accuracy. Future improvements will focus on increasing model transparency and adaptability to evolving DeepFake generation techniques.
