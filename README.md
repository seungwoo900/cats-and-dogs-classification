# 🐱🐶 Cats vs Dogs Classifier (VGG16 + Grad-CAM)

## 📌 Project Overview
This project uses **VGG16** to classify images of cats and dogs.  
Additionally, **Grad-CAM (Gradient-weighted Class Activation Mapping)** is applied to visualize which areas of the image influenced the model's decision.  

- **Pretrained VGG16 Model:** Transfer learning with fine-tuning.  
- **Binary Classification:** Cat 🐱 vs. Dog 🐶  
- **Grad-CAM:** Visualizing feature activation before and after training.  

---

## 🗂 Dataset
I use the **Cats vs Dogs dataset** from Kaggle.  

- **Download from Kaggle:**  
  - Dataset: [Cats vs Dogs Dataset](https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset)  
  - Use the Kaggle API to download the dataset:
    ```bash
    kaggle datasets download -d tongpython/cat-and-dog
    unzip cat-and-dog.zip -d ./dataset
    ```

---

## 🚀 How to Run
```bash
pip install -r requirements.txt

```bash
jupyter notebook cats_dogs_classifier.ipynb

Train the model
