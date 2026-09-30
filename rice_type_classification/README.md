# 🌾 Rice Type Classification

This project aims to classify two different types of rice using their numerical and morphological features (such as area, perimeter, major/minor axis lengths, etc.) by implementing a Deep Learning approach. 

Data preprocessing, Artificial Neural Network (ANN) architecture design, model training, and testing phases were all conducted end-to-end using PyTorch within a single Jupyter Notebook.

## 📂 Dataset
This project uses the tabular [Rice Type Classification](https://www.kaggle.com/datasets/mssmartypants/rice-type-classification) dataset available on Kaggle.

* **Data Type:** Numerical / Tabular Data
* **Classes (2):** Jasmine - 1, Gonen - 0 
* **Features:** Numerical columns representing the physical dimensions of the rice grains.

## 🛠️ Technologies Used
* **Language:** Python
* **Deep Learning:** PyTorch 
* **Data Processing:** Pandas, NumPy, Scikit-learn (for data scaling and train/test split)
* **Visualization:** Matplotlib (for plotting loss and accuracy curves)
* **Environment:** Jupyter Notebook

## ⚙️️ Setup and Execution

To run or examine the project on your local environment, follow these steps:

1. Clone the repository:
   git clone [https://github.com/OguzhanB16/Deep-Learning.git](https://github.com/OguzhanB16/Deep-Learning.git)
   
2. Navigate to the project directory:
  cd Deep-Learning/rice_type_classification

3.Ensure the required libraries are installed:
  pip install torch pandas numpy scikit-learn matplotlib

4.Launch Jupyter Notebook and open the project file:
  jupyter notebook rice_type_classification.ipynb

  Results:

<img width="1321" height="487" alt="image" src="https://github.com/user-attachments/assets/87e77e6f-fb9c-4b48-a542-ecd4b1a8e5cd" />

