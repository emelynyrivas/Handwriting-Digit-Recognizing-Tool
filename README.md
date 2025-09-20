# ✨ Handwritten Digit Recognition Project
This is a handwritten digit recognizing tool that uses a machine learning application that recognizes handwritten digits using a **Convolutional Neural Network (CNN)** trained on the MNIST dataset.  

The model is also tested with my **own sample handwritten images** to validate performance outside the training set.  

---

⚠️ Note:
- This project is pre-trained, and you will need access to the finetuned model.
- There is a small dataset that I created to help train this modle. You will need access to this folder as well.

**Both of these files are stored in a shared Google Drive. Instructions for accessing them are below.**  


---

##  How to Run This Project

Please click that link here for the shared folder in google drive: https://drive.google.com/drive/folders/1jNUN0KzmVFEYNcywKZ_wAZVgbgOvbOLd?usp=sharing

The folder's path should be:  /content/drive/MyDrive/Drive files for digit handwriting tool

*The order is very important*

### 1. Open the Notebook in Google Colab
Click the badge below to open the notebook directly in Colab:


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/emelynyrivas/Handwriting-Digit-Recognizing-Tool/blob/main/Handwriting_Digit_Recognizing_Tool.ipynb)

---

### 2. Mount Google Drive
In the first code cell of the notebook, run:
```python
from google.colab import drive
drive.mount('/content/drive')
```
---

### 3. Update file paths
Make sure the following paths match the location of your files in Drive:

  - Path of finetuned model = "/content/drive/MyDrive/Drive files for digit handwriting tool/mnist_digit_cnn_finetuned.h5"

  - Path of sample data folder = "/content/drive/MyDrive/Drive files for digit handwriting tool/handwriting_samples"

---

### 4. Run all the cells

  Select Runtime → Run all in Colab.

  The notebook will:
  - Load the trained CNN model
  - Preprocess and clean the dataset
  - Perform predictions on both MNIST test data and our sample data
  - Display visualizations of results

