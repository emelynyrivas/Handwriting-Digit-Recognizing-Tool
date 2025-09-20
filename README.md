# ✨ Handwritten Digit Recognition Project
This is a handwritten digit recognizing tool that uses a machine learning application that recognizes handwritten digits using a **Convolutional Neural Network (CNN)** trained on the MNIST dataset.  

The model is also tested with my **own sample handwritten images** to validate performance outside the training set.  

---

⚠️ Note:
- You must have a Google account in order to use this project.
- This project is pre-trained, and you will need access to the finetuned model.
- There is a small dataset that I created to help train this modle. You will need access to this folder as well.

**Both of these files are stored in a shared Google Drive. Instructions for accessing them are below.**  


---

##  How to Run This Project

- Log into your Google Account

- Please click that link here for the shared folder in google drive: https://drive.google.com/drive/folders/1jNUN0KzmVFEYNcywKZ_wAZVgbgOvbOLd?usp=sharing

- After you click the link, the shared folder should be on a tab that says "Shared with me" in the left side tab.
- Click the three red dots on the right side of the folder and click "Download"
  <img width="1269" height="533" alt="Screen Shot 2025-09-20 at 3 34 20 PM" src="https://github.com/user-attachments/assets/ab4b2f3a-efbb-4a33-bee2-26c81951fb94" />

- The folder will then download as a zip file. Unzip it and add the folder to your Google Drive.
- The folder's path should be:  /content/drive/MyDrive/Drive files for digit handwriting tool

    **The order is very important!**

- Click on "MyDrive" on the left side tab to make sure the folder is in there:
  <img width="1239" height="489" alt="Screen Shot 2025-09-20 at 3 41 24 PM" src="https://github.com/user-attachments/assets/231a66a8-85b5-4217-b7c0-04d68f28a4b4" />


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

A pop up will appear and ask you if Colab can have access to your Google Drive. Click accept all.

---

### 3. Verify file paths
Make sure the following paths match the location of your files in Drive:

  - Path of finetuned model = "/content/drive/MyDrive/Drive files for digit handwriting tool/mnist_digit_cnn_finetuned.h5"

  - Path of sample data folder = "/content/drive/MyDrive/Drive files for digit handwriting tool/handwriting_samples"

    *You can verify the paths by making sure the shared folder is located here in colab:*
    
    <img width="1266" height="383" alt="Screen Shot 2025-09-20 at 3 54 43 PM" src="https://github.com/user-attachments/assets/d487a033-423a-4b43-a570-d281e2ee3ad6" />


---

### 4. Run all the cells

  On the top right in Colab, click "Runtime" → "Run all"
  
  <img width="1105" height="505" alt="Screen Shot 2025-09-20 at 3 57 49 PM" src="https://github.com/user-attachments/assets/5de058dc-aa83-422c-bc08-e9935968dc2f" />


  The notebook will:
  - Load the trained CNN model
  - Preprocess and clean the dataset
  - Perform predictions on both MNIST test data and our sample data
  - Display visualizations of results


### 5. Use the user friendly application

  Scroll to the very bottom of the page to use the application. Follow the directions.
  
  <img width="995" height="438" alt="Screen Shot 2025-09-20 at 4 05 20 PM" src="https://github.com/user-attachments/assets/9ecfef1a-3d36-477a-8e6e-d5971910787e" />
