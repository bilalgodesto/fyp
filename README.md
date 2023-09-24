# Developing a Vision-Language Multimodal Learning Approach for Quantifying Public Perceptions of Landscape Scenicness

## Files:

- **Preprocessing.ipynb**
- **ResNet50.ipynb**
- **ViLT.ipynb**
- **BERT.ipynb**

## Tes Models
- **TEST_VILT.ipynb**
- **TEST_BERT_template.ipynb**
- **TEST_RESNET50.ipynb**

---

### Preprocessing.ipynb

**Objective:** This notebook covers the preprocessing of our dataset, which consists of approximately 210,000 landscape images. Each image is paired with textual comments and assorted metadata, including geographical coordinates and voting statistics. Data integration was vital, involving the harmonization of multiple files, such as `votes.tsv`, `scenicornot.csv`, and `gridimage text.csv`, based on shared attributes like `gridimage id`. We diligently addressed data integrity issues by excluding entries with missing Geograph URLs or comments. Textual data underwent comprehensive preprocessing, such as contraction expansion, HTML tag removal, and lemmatization. We also crafted critical features, like average and variance, from the voting data to quantitatively represent scenicness.

[votes.tsv](https://drive.google.com/uc?id=1JesG06eSXlBCnAVx7liCHREIsFm7bvni)
[scenicornot.csv](https://drive.google.com/uc?id=1kpNNeOQhONxDZV57bCHVANTpLookqHoB)
[gridimage_text.csv](https://drive.google.com/uc?id=1BjI1NI3Td63sqlBpHp80I1NTe58OpEqx)

**Instructions for Code Execution:** This file can be run directly without any special permissions.


### DataSets

[Traning Dataset](https://drive.google.com/uc?id=1eyUZPqxU1H-heqZHFhQ74hqp5rlBLWsA)

[Testing Dataset](https://drive.google.com/uc?id=1eX9AKnj2ALQt9dD3n_UcFGe3mO7uXuiS)

[Validation Dataset](https://drive.google.com/uc?id=17f9oKnzUBI_5EaL_cg40zdL6eneWxZNY)

[Qualtative Dataset](https://drive.google.com/uc?id=1-39gatpZL3__lLx3CY90jJFqLxPQ3w8q)


### Compiled Models

[ResNet50](https://fypphotos.s3.amazonaws.com/resnet_model_final_presentation.pth)

[BERT](https://fypphotos.s3.amazonaws.com/resnet_model_final_presentation.pth)

[ViLT](https://fypphotos.s3.amazonaws.com/pytorch_model.bin)



---

### ResNet50.ipynb

**Objective:** This notebook entails the creation and training process for the ResNet50 model. [add more details here]


**Instructions for Code Execution:**

To ensure smooth execution of the code, please follow the steps below carefully:

### Step 1: Accessing the Public Folders
While our image folders are shared publicly on Google Drive, you still need to create a shortcut for them in your drive to access them smoothly. Follow the instructions below to do so:

1. **Requesting Access**:
    - The folders, while public, might still require explicit access. If so, please request access by sending an email to [bilal2.rabbi@live.uwe.ac.uk](mailto:bilal2.rabbi@live.uwe.ac.uk).

2. **Creating a Shortcut**:
    - Navigate to the shared folder on Google Drive.
    - Right-click on the desired folder.
    - From the context menu, hover over `Organize` to reveal further options.
    - Click on `Add Shortcut to My Drive`.
    - Choose the location in `My Drive` where you'd like to place the shortcut and confirm.

### Step 2: Running the Code

Once you've successfully added the shortcut to your drive, you can proceed to run the provided code. Ensure the code references the correct paths, matching where you've added the shortcuts in your Google Drive.

---

By following the above instructions carefully, you should face no issues accessing the images and running the code. If you encounter any issues, please reach out for further assistance.


---

### ViLT.ipynb

**Objective:** This notebook is dedicated to the creation and training process of the ViLT model. [add more details here]

## Instructions for Accessing and Running the Code

To ensure smooth execution of the code, please follow the steps below carefully:

### Step 1: Accessing the Public Folders
While our image folders are shared publicly on Google Drive, you still need to create a shortcut for them in your drive to access them smoothly. Follow the instructions below to do so:

1. **Requesting Access**:
    - The folders, while public, might still require explicit access. If so, please request access by sending an email to [bilal2.rabbi@live.uwe.ac.uk](mailto:bilal2.rabbi@live.uwe.ac.uk).

2. **Creating a Shortcut**:
    - Navigate to the shared folder on Google Drive.
    - Right-click on the desired folder.
    - From the context menu, hover over `Organize` to reveal further options.
    - Click on `Add Shortcut to My Drive`.
    - Choose the location in `My Drive` where you'd like to place the shortcut and confirm.

### Step 2: Running the Code

Once you've successfully added the shortcut to your drive, you can proceed to run the provided code. Ensure the code references the correct paths, matching where you've added the shortcuts in your Google Drive.

---

By following the above instructions carefully, you should face no issues accessing the images and running the code. If you encounter any issues, please reach out for further assistance.


---

[Further sections can be added similarly for other files like BERT.ipynb]

---

### Additional Notes:

- Ensure you have all the necessary dependencies installed before running the notebooks.
- It's recommended to run the notebooks in a virtual environment to avoid any package conflicts.

---


#### Contribution:

We will be soon starting to accept PR requests

