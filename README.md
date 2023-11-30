# Image Classification Project

## Overview

This project involves building a deep learning model for image classification, capable of distinguishing between happy and sad images. The model is trained on a dataset containing images of happy and sad faces.

## Project Structure

- **data:** Contains training images organized into 'happy' and 'sad' directories.
- **models:** Holds the saved Keras model file (`happysadmodel.keras`).
- **notebooks:** Jupyter notebooks for data preprocessing, model training, and testing.
- **logs:** Logs for TensorBoard visualization (TensorBoard is optional and used for model training monitoring).

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Load Pre-trained Model (Optional):**
   - If you only want to use the pre-trained model without retraining, follow the instructions in the notebook or use the provided `happysadmodel.keras` file.

4. **Run Inference:**
   - Use the provided Jupyter notebook or script to run inference on your own images.

## Results and Evaluation

- View the training and validation loss/accuracy using TensorBoard or by visualizing the training history in the notebook.

## Making Predictions

1. **Run Inference on New Images:**
   - Use the provided Jupyter notebook to make predictions on new images.

## Notes

- This model is trained on a limited dataset, so results may vary on new, unseen data.
- Feel free to experiment, contribute, or use the pre-trained model for your own applications.
