# GiziWise - Machine Learning Notebook

## Project Overview
GiziWise is an app made by C23-PS450 students for Bangkit 2023 Capstone Project. GiziWise is an application that helps people discover the composition and nutritional content of food and beverages by capturing images through the camera or gallery. These images are then analyzed, providing detailed information about the uploaded pictures within the GiziWise application. Moreover, users can also find articles and recipes for healthy food.

## Our Machine Learning Team
* M037DSX0368 - Firmansyah Davin Falahtama
* M181DSY3522 - Cya Dessylia

## Dataset Description

We have trained a machine learning model using a comprehensive dataset of processed food images. The dataset was sourced from multiple reliable sources, including Kaggle.com, and additional data was scraped from Google. The dataset consists of a total of 7200 images, covering a wide range of food items, which have been categorized into 20 distinct classes.

The dataset provides:

- A diverse collection of food images for robust training and evaluation of machine learning models.
- Preprocessed images to ensure consistent quality and standardization.

**Dataset Split:**

The dataset has been partitioned into three subsets:

* Training Set: 6000 images specifically curated for model training.
* Testing Set: 600 images reserved for model evaluation and generalization assessment.
* Validation Set: 600 images for fine-tuning and hyperparameter optimization.

**Accessing the Dataset:**

To access the dataset, please find the following links:

1. [Google Drive - Processed Food Images Dataset](https://drive.google.com/drive/folders/1l4IW0IxnJgCTrCgHZuoToQbmnNNzBJBP?usp=drive_link)
2. [Kaggle - Indonesian Food Dataset](https://www.kaggle.com/datasets/rizkashintaw/indonesian-food)
3. [Kaggle - Food41 Dataset](https://www.kaggle.com/datasets/kmader/food41)

We express our gratitude to the contributors of the original datasets for making them publicly available, enabling research and development in the field of food image analysis.

## Training Instructions

To train the machine learning model using the provided dataset, follow these steps:

1. **Access the dataset**: Download the dataset from the [Google Drive](https://drive.google.com/drive/folders/your-folder-id) link provided. Alternatively, for convenience, you can add the dataset's Google Drive folder to your own drive by creating a shortcut.

2. **Open the notebook**: Upload the [GiziWise_Dense.ipynb](https://github.com/gizi-wise/gizi-wise-ML/blob/main/GiziWise_Dense.ipynb) notebook in Google Colab by clicking on the link.

3. **Mount Google Drive**: In the Colab notebook, execute the following code snippet to mount your Google Drive and provide authorization:

   ```python
   from google.colab import drive
   drive.mount('/content/drive')

Follow the instructions to authenticate and grant necessary permissions to access your Google Drive.

4. **Upload the dataset**: In the Colab notebook, upload the dataset files you downloaded in step 1 to the mounted Google Drive. If you added a shortcut to the dataset's folder in your drive, you can directly access it. Otherwise, use the code snippet to upload the files and make sure the dataset files are in the same directory as the notebook.

5. **Run the notebook**: Execute the code cells in the notebook one by one to train the machine learning model. Review the code comments for any specific instructions or parameters you may need to modify.

Note: If required, adjust the paths or filenames in the notebook to match the names of the uploaded dataset files or the location of the dataset in your Google Drive.
