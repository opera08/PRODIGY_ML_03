### Dogs vs Cats Image Classification

This repository contains code for a simple Dogs vs Cats image classification task using Support Vector Machines (SVM) with a linear kernel. The dataset used for this task is the Dogs vs Cats dataset available on Kaggle.

#### Dataset
- The dataset consists of images of cats and dogs.
- You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/salader/dogs-vs-cats) and place the ZIP file in the root directory of this repository.
- After downloading, extract the contents of the ZIP file.

#### Installation
1. Clone this repository to your local machine:
   ```
   git clone https://github.com/your-username/your-repo.git
   ```
2. Navigate to the repository directory:
   ```
   cd your-repo
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

#### Usage
1. **Data Preparation:**
   - Ensure the dataset is extracted and available in the repository directory.
   - The dataset should contain subdirectories for 'cats' and 'dogs' images.

2. **Training:**
   - Run the provided Jupyter notebook or Python script to train the SVM model.
   - The script preprocesses the images, splits them into training and testing sets, and trains the SVM model.
   - Optionally, experiment with different preprocessing techniques or machine learning algorithms for better performance.

3. **Evaluation:**
   - The trained SVM model is evaluated using the test set, and the accuracy of the classification task is displayed.

4. **Model Persistence:**
   - The trained SVM model and PCA object (used for dimensionality reduction) are pickled and saved as `linear_svm_model.pickle` and `pca_object.pickle`, respectively.

5. **Sample Usage (Optional):**
   - The repository includes code for a sample demonstration of loading and preprocessing images for classification.
   - You can modify the image paths and predictions to test the model with your own images.

#### Files
- **linear_svm_model.pickle:** Pickled file containing the trained SVM model.
- **pca_object.pickle:** Pickled file containing the PCA object used for dimensionality reduction.
- **README.md:** Instructions and information about the repository.

#### Note
- Ensure correct file paths and permissions for accessing the dataset and model files.
- Feel free to explore and modify the code for experimenting with different machine learning algorithms or image preprocessing techniques.
- For any issues or suggestions, please open an issue in the repository or contact the repository owner.

### License
This project is licensed under the [MIT License](LICENSE).
