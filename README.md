# Brain Tumor Detection

This project focuses on detecting brain tumors in medical images using machine learning techniques. The code provided utilizes a pre-trained VGG16 model to extract features from brain images and then trains a support vector machine (SVM) classifier to classify the images as either tumorous or non-tumorous.

## Dataset

The dataset used in this project consists of brain images categorized into two classes: "yes" (tumorous) and "no" (non-tumorous). The dataset is loaded and preprocessed, including cropping the brain area and resizing the images.

## Dependencies

- numpy
- matplotlib
- cv2 (OpenCV)
- scikit-learn
- tensorflow

## Usage

1. Ensure you have the required dependencies installed.

2. Load the dataset:

   - Place the tumorous brain images in the folder path: `/path/to/yes`.
   - Place the non-tumorous brain images in the folder path: `/path/to/no`.
   - Update the `yes` and `no` folder paths in the code.

3. Specify the image size in the `IMG_WIDTH` and `IMG_HEIGHT` variables.

4. Run the code:

   Execute the provided code in a Python environment, such as Jupyter Notebook or any Python IDE.

5. Model Training and Evaluation:

   The code utilizes the pre-trained VGG16 model to extract features from the training images. The SVM classifier is then trained using these features and evaluated on the test set.

## Results

The accuracy, precision, recall, and F1 score of the SVM classifier on the test set are displayed.
