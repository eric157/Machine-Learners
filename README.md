# 🌟 Machine Learners: Machine Learning Group Assignments & ML 100 Min Challenge 🌟

## **Overview** 📚

This repository contains solutions to various machine learning tasks completed by the **Machine Learners** team. The tasks are organized into four main categories:

1. **Regression** 📉 - Predicting continuous values (Dairy Goods Sales Dataset)
2. **Classification** 🔍 - Predicting discrete labels from input features (Amazon Products Dataset)
3. **Unsupervised Learning** 🔎 - Extracting meaningful patterns from unlabeled data (Customer Support on Twitter Dataset)
4. **ML 100 Min Challenge** ⏱️ - Solving multiple machine learning challenges in under 100 minutes

---

## **Project Structure** 📁

```bash
Machine-Learners/
├── Regression/                           # Contains regression models 📈
│   ├── dairy_dataset.csv                # Dataset for regression task (Dairy Goods Sales) 🧀
│   └── Regression_MachineLearners.ipynb  # Jupyter Notebook for regression task 📝
│
├── Classification/                       # Contains classification models 🛍️
│   ├── Amazon-Products.zip               # Raw dataset for classification (Amazon Products) 📦
│   └── Classification_T5.ipynb           # Jupyter Notebook for classification task 🧑‍💻
│
├── Unsupervised/                        # Contains unsupervised learning tasks 🧠
│   └── T5-Unsupervised.ipynb            # Jupyter Notebook for unsupervised learning task 🔍
│
├── 'ML Challenge'/                       # ML 100 Min Challenge folder ⏱️
│   ├── ML_Challenge1_T5.ipynb           # Jupyter Notebook for first ML challenge 🏆
│   ├── ML_Challenge2_T5.ipynb           # Jupyter Notebook for second ML challenge 🏅
│
└── README.md                            # This file 📄
```

---

## **Team Members** 👨‍💻👩‍💻

- 202418013 - **Darshita Dwivedi**
- 202418025 - **Kelvi Bhesdadiya**
- 202418057 - **Eric Thomas**
- 202418058 - **Ujjwal Bhansali**

---

## **Subprojects Overview** 🔍

### **1. Regression** 📊  
This subproject focuses on predicting continuous values using machine learning. We use a **Dairy Goods Sales Dataset** to apply regression models.

- **dairy_dataset.csv**: The dataset contains information on dairy product sales. The goal is to predict continuous values such as sales amounts.
- **Regression_MachineLearners.ipynb**: The Jupyter notebook where data is processed, various regression models are trained, and predictions are made on sales values in the dairy goods industry.

### **2. Classification** 🏷️  
This subproject aims to classify e-commerce products into categories based on product names. We use the **Amazon Products Dataset** for this task.

- **Amazon-Products.zip**: A dataset that contains product names and categories from Amazon.
- **Classification_T5.ipynb**: This notebook covers the steps of text cleaning, feature extraction (e.g., TF-IDF), and training classification models (e.g., Logistic Regression, Random Forest) to predict product categories.

### **3. Unsupervised Learning** 🧠  
The **Unsupervised Learning** subproject aims to identify meaningful patterns in unlabeled data. The dataset used involves customer support interactions on Twitter.

- **T5-Unsupervised.ipynb**: This notebook applies unsupervised learning techniques like clustering, dimensionality reduction, and pattern recognition to customer support interactions on Twitter.
- **Dataset**: [Customer Support on Twitter](https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter)

### **4. ML 100 Min Challenge** ⏳  
This folder contains solutions to the **ML 100 Min Challenge**, where we solve multiple machine learning tasks in under 100 minutes.

- **ML_Challenge1_T5.ipynb**: The first challenge in the ML 100 Min Challenge, where we apply a machine learning model to solve the problem.
- **ML_Challenge2_T5.ipynb**: The second challenge in the ML 100 Min Challenge, continuing from the first with a new dataset and task.

---

## **How to Run the Project** 🚀

### **1. Install Dependencies** ⚙️

To run the notebooks, install the required dependencies. It is recommended to use a virtual environment:

```bash
pip install -r requirements.txt
```

The `requirements.txt` includes essential libraries such as:
- `numpy`
- `pandas`
- `sklearn`
- `matplotlib`
- `seaborn`
- `plotly`
- `nltk`

### **2. Running the Notebooks** 💻

- Navigate to the respective folder (e.g., **Regression**, **Classification**, or **Unsupervised**) depending on your task.
- Open the relevant Jupyter Notebook (`.ipynb`) in a Jupyter notebook environment (e.g., JupyterLab or Google Colab).
- Execute the cells step-by-step to see the outcomes of each stage in the machine learning pipeline.

---

## **Description of Files** 🗂️

### **Regression Folder** 📉
- **dairy_dataset.csv**: Contains data related to dairy goods sales, used for regression tasks.
- **Regression_MachineLearners.ipynb**: This notebook handles data analysis, model training, and sales predictions in the dairy goods sector.

### **Classification Folder** 🛒
- **Amazon-Products.zip**: A dataset with product information such as names and categories for classification tasks.
- **Classification_T5.ipynb**: This notebook involves text preprocessing, feature extraction, and model training (Logistic Regression, Random Forest) to classify products.

### **Unsupervised Folder** 🔍
- **T5-Unsupervised.ipynb**: Explores unsupervised learning techniques, such as clustering and dimensionality reduction, applied to customer support data.
- **Dataset**: [Customer Support on Twitter](https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter)

### **ML Challenge Folder** ⏱️
- **ML_Challenge1_T5.ipynb**: Solution for the first ML challenge task.
- **ML_Challenge2_T5.ipynb**: Solution for the second ML challenge task.

---

## **Acknowledgements** 🙏

- **Dataset Sources**:
  - **Amazon Products**: [Kaggle - Amazon Products Dataset](https://www.kaggle.com/datasets/lokeshparab/amazon-products-dataset)
  - **Dairy Goods Sales**: [Kaggle - Dairy Goods Sales Dataset](https://www.kaggle.com/datasets/suraj520/dairy-goods-sales-dataset/data)
  - **Customer Support on Twitter**: [Kaggle - Customer Support on Twitter](https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter)
  
- **Libraries Used**:
  - `numpy`, `pandas`, `sklearn`, `matplotlib`, `seaborn`, `plotly`, `nltk`

---

## **Future Work** 🚀

- **Classification**: Experiment with deep learning models like CNNs or LSTMs to potentially enhance performance.
- **ML Challenge**: Continue tackling additional challenges and applying more advanced machine learning techniques.
- **Regression**: Incorporate additional features to improve the prediction accuracy.
- **Unsupervised Learning**: Test different clustering algorithms and dimensionality reduction techniques to better understand data patterns.
