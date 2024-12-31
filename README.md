# Food Image 101 Classes Classifier - Computer Vision
This repository contains a project focused on classifying images of **101** different food classes using deep learning and computer vision techniques. The project leverages transfer learning and fine-tuning with TensorFlow to achieve a high accuracy of **80%** on the full test set, exceeding the baseline accuracy of 50.76% reported in the original Food101 paper using only **10%** of the training data, and surpasses the 77.4% accuracy benchmark established by the DeepFood paper using **100%** of the training data. The implementation is carried out on Google Colab for efficient computation and easy accessibility.

---

## Key Features
- **Data Source:** Preprocessed food image datasets derived from the 'Organizing_The_Food101_Dataset' notebook. Additionally, we are using the same dataset from TensorFlow datasets (TFDS) for some models.
- **Deep Learning Framework:** TensorFlow
- **Model Type:** Deep Learning, Computer Vision, Transfer Learning Feature Extraction, and Transfer Learning Fine-Tuning with Data Augmentation
- **Goal:** Classifying images into **101** different food classes, exceeding the baseline accuracy of 50.76% reported in the original Food101 paper using only **10%** of the training data, as well as the 77.4% accuracy benchmark established by the DeepFood paper using 100% of the training data
- **Accuracy:** Achieves **80%** accuracy on the full test set
- **Environment:** Google Colab for development and execution

---

## Repository Contents
- **Notebooks:**
  - **Organizing_The_Food101_Dataset:** Notebook for preparing and organizing the Food-101 dataset from Kaggle.
  - **Food Image 101 Classes Classifier - Computer Vision:** Notebook detailing the data loading and preprocessing, model training, evaluation, prediction, and results.
- **Scripts:**
  - **helper_functions.py:** Contains utility functions needed for the project, located in the 'scripts' folder.
- **Data:** Preprocessed datasets available through publicly accessible Google Drive links in the 'Food Image 101 Classes Classifier - Computer Vision' notebook, along with datasets from TensorFlow Datasets (TFDS).

---

## Getting Started
1. **Clone the repository:**
```bash
git clone! https://github.com/IsraelAzoulay/food-image-101-classes-classifier-computer-vision.git
```

2. **Open the provided Google Colab notebooks:**
Navigate to the `notebooks` folder and open the desired notebook in Google Colab.
3. **Run the Notebooks:**
Follow the instructions in the notebooks to download the datasets, preprocess the data, train, evaluate and predict with the models.
4. **Customize:**
Feel free to modify the models and code for your experiments.

---

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

---

## License
This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) License.
