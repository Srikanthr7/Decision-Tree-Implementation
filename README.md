# 🌳 Decision Tree Classifier - Iris Dataset

This project demonstrates the implementation of a **Decision Tree Classifier** using the **Iris dataset**.  
The notebook includes **data preprocessing, model training, visualization, and evaluation**.  

---

## 📌 Dataset

We use the **Iris dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data).  

- **Features:**  
  - Sepal Length  
  - Sepal Width  
  - Petal Length  
  - Petal Width  

- **Target Classes:**  
  - Setosa  
  - Versicolor  
  - Virginica  

---

## 🚀 Implementation Steps

1. **Import libraries**  
   - `pandas`, `numpy`, `matplotlib`, `seaborn`  
   - `sklearn` (DecisionTreeClassifier, train_test_split, metrics)  

2. **Load dataset**  
   - Read Iris dataset directly from UCI link  

3. **Preprocessing**  
   - Split features (`X`) and labels (`y`)  
   - Train-Test Split (70:30)  

4. **Model Training**  
   - Use `DecisionTreeClassifier` with `criterion="entropy"` and `max_depth=3`  

5. **Evaluation**  
   - Classification report  
   - Accuracy score  
   - Confusion matrix  

6. **Visualization**  
   - Plot confusion matrix heatmap  
   - Plot decision tree structure  
   - Export rules in text format  

---

## 📊 Results

- **Accuracy:** ~95-100% (depends on random split)  
- **Tree Visualization:** Clearly shows decision rules for classification  

---

## 🖥️ How to Run

### 🔹 Option 1: Run in Google Colab
- Open the notebook in Colab  
- Run the cells step by step  

### 🔹 Option 2: Run Locally
```bash
# Clone this repository
git clone https://github.com/your-username/decision-tree-iris.git
cd decision-tree-iris

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook Decision_Tree.ipynb
