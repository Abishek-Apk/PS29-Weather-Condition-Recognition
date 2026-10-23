# Weather Condition Recognition from Outdoor Images

## Project Overview
This project uses deep learning and transfer learning to classify outdoor images into four weather-related categories: Cloudy, Rain, Shine, and Sunrise.

## Technologies Used
- Python
- TensorFlow and Keras
- MobileNetV2
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Dataset
The dataset contains 1,125 images across four classes:
- Cloudy: 300 images
- Rain: 215 images
- Shine: 253 images
- Sunrise: 357 images

Dataset source: https://data.mendeley.com/datasets/4drtyfjtfy/1

## Methodology
1. Load and inspect the dataset.
2. Split images into training, validation, and testing sets.
3. Apply image preprocessing and data augmentation.
4. Use MobileNetV2 transfer learning for image classification.
5. Train and evaluate the model using classification metrics.

## Results
- Best validation accuracy: 95.27%
- Test accuracy: 93.49%
- Test loss: 0.1755

The model was evaluated using per-class precision, recall, F1-score, and a confusion matrix.

## How to Run
1. Open `PS29_Weather_Recognition.ipynb` in Google Colab.
2. Upload the required dataset ZIP file when prompted.
3. Run the notebook cells in order.
4. Review the training and evaluation results.

## Limitations
Performance may vary on images from different environments. The dataset was not independently audited for duplicate images, and further robustness testing is recommended.

## Author
Add your name here.
