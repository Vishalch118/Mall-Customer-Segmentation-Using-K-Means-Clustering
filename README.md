# 🛍️ Customer Segmentation using K-Means Clustering

This project demonstrates how to perform **customer segmentation** using the **K-Means Clustering** algorithm.  
By analyzing purchasing behavior and demographic data, we can group customers into segments that share similar characteristics — a key step in targeted marketing and business strategy.

## 🧩 Introduction

**K-Means Clustering** is an unsupervised machine learning algorithm used to partition data into *k* groups (clusters).  
This notebook applies K-Means to segment customers based on their **Annual Income** and **Spending Score**, revealing patterns in purchasing behavior.

The notebook walks through the complete process:

1. Importing dependencies  
2. Loading and inspecting the dataset  
3. Cleaning data and checking for missing values  
4. Applying the **Elbow Method** to determine optimal *k*  
5. Training the **K-Means model**  
6. Visualizing customer clusters  

---

## 📊 Dataset

This notebook typically uses the **Mall Customers Dataset**, which includes columns such as:
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1–100)`

Example Kaggle dataset:  
🔗 [Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)

---

## ⚙️ Features

- Automatic detection of the optimal number of clusters (Elbow Method)
- Clean visualizations using **matplotlib** and **seaborn**
- Easy-to-run notebook — no manual configuration needed
- Clearly segmented results and labeled clusters
- Ideal for learning or business analytics use cases

---

## 💻 Installation

To run this project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/Vishalch118/Mall-Customer-Segmentation-Using-K---Means-Clustering
# Navigate into the project directory
cd Mall-Customer-Segmentation-Using-K---Means-Clustering

# Install dependencies
pip install -r requirements.txt
```
## Dependencies

Make sure you have the following Python libraries installed:
```
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```
## 📈 Results

After training the K-Means model, the notebook produces:

Elbow Method Plot – to find the best number of clusters (k) 
We must decide the k value by finding the point where there is a sudden drop in the curve, take the X cordinate of that point as k
in case of multiple sudden drops take the point which gives steep drop. 
example : 
<p align="center">
  <img src="Screenshot 2025-11-02 122133.png" alt="Customer Clusters" width="350"/>
</p>


Cluster Visualization – showing customer segmentation based on spending score and annual income

Example Segments:

Low income, low spending

Low income, high spending

Average income, average spending

High income, low spending

High income, high spending

These segments can help businesses better target customer groups with tailored marketing strategies.


👥 Contributors

Your Name — GitHub Profile

Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

🪪 License

This project is licensed under the MIT License.
See the LICENSE
 file for details.

🔗 References

Scikit-learn: K-Means Clustering : https://scikit-learn.org/stable/modules/clustering.html#k-means

Kaggle: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

Matplotlib Documentation : https://matplotlib.org/stable/users/index.html

Seaborn Documentation : https://seaborn.pydata.org/
