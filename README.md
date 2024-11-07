# Trash Classification Model

This repository contains code for training a Convolutional Neural Network (CNN) model to classify images of trash. The model is trained on the **TrashNet** dataset, which is available through the Hugging Face datasets library.

## Project Overview

The goal of this project is to build a machine learning model that can classify images of trash into categories such as plastic, metal, paper, etc. This model could potentially be used in applications to aid in waste management and recycling efforts.

## Dataset

The dataset used for this project is **TrashNet**, a labeled collection of images of different types of trash. We load this dataset using the [Hugging Face Datasets library](https://huggingface.co/docs/datasets).
The dataset includes the following classes:
- Plastic
- Metal
- Paper
- Cardboard
- Glass
- Trash (other miscellaneous items)

## Prerequisites

- Python 3.7 or higher
- Git
- [Hugging Face Datasets](https://github.com/huggingface/datasets), TensorFlow, and other dependencies listed in `requirements.txt`

## Usage
1. Clone the repository
```
git clone https://github.com/ardrkha/trash-classification.git
cd trash-classification
```

2. Run the notebook
```
trash-classification/
├── notebook/
│   ├── [Notebook.ipynb] (run this notebook for the complete implementation)
├── README.md
└── ...
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions, feel free to reach out to us at hardatama27@gmail.com.

---

Developed by Hardatama Rakha Ugraha - 2024
