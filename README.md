# Cancerous and Non-Cancerous Skin Lesion Detection

This repository contains the code and dataset for the "Cancerous and Non-Cancerous Skin Lesion Detection" project, which was developed as a Machine Learning term project. The goal of this project is to detect cancerous and non-cancerous skin lesions using machine learning techniques, with the primary objective of improving the accuracy and efficiency of skin cancer diagnosis.

## Motivation
Skin cancer is one of the most prevalent types of cancer worldwide, and early detection is crucial for successful treatment and improved patient outcomes. Traditional methods of diagnosis can be time-consuming and may not always yield accurate results. This project aims to utilize machine learning algorithms to provide a more reliable and efficient approach to identify cancerous and non-cancerous skin lesions.

## Dataset
The dataset used for this project is classified into 7 classes:
- Cancerous Lesions: Melanoma, Basal Cell Carcinoma, Actinic Keratoses, Melanocytic Nevi
- Non-Cancerous Lesions: Benign Keratosis, Vascular Lesions, Dermatofibroma

## Model
We employed the ResNet-50 model for this task. The model was trained on our dataset and achieved a training accuracy of 94.2%. The pre-trained ResNet-50 model has demonstrated strong performance in various computer vision tasks and is well-suited for image classification tasks like skin lesion detection.

## Usage
The code provided in this repository includes the necessary scripts for data processing, model training, and evaluation. To use the project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Place the dataset in the appropriate directory (or update the data paths in the code).
4. Execute the data preprocessing scripts (if necessary) to prepare the data for training.
5. Run the training script to train the ResNet-50 model on the dataset.
6. After training, the model can be saved and used for inference in real-time applications.

## Dependencies
The following libraries are required to run the project:
- os, cv2, itertools
- matplotlib, numpy, pandas, tqdm
- PIL (Python Imaging Library)
- torch (PyTorch)
- sklearn (scikit-learn)

Make sure to have these libraries installed before running the project.

## Data
The dataset used in this project is not provided in this repository due to its large size and licensing restrictions. However, you can obtain a similar dataset from publicly available sources or medical research repositories. Ensure that you have the dataset organized according to the expected structure for the data preprocessing scripts to work correctly.

## Acknowledgments
We would like to acknowledge the invaluable guidance and support of our instructors and peers during the course of this project.

## Future Improvements
While the current implementation has achieved a promising accuracy of 94.2%, there is always room for improvement. Some potential areas for future enhancements include:

- Exploring other state-of-the-art deep learning architectures and comparing their performance with ResNet-50.
- Investigating data augmentation techniques to expand the dataset and potentially improve generalization.
- Fine-tuning hyperparameters to achieve better model performance.
- Incorporating an interface for real-time inference, allowing users to upload images and get instant predictions.

Contributions and suggestions for improvements are welcome from the community.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
