# 🚀 Hyper-Personalized Customer Intelligence Engine
**Developing a High-Resolution RFM Segmentation Model for Retail Strategy**

## 📌 Project Overview
This project transforms over **1.06 million rows** of transactional data into actionable business segments. Using **K-Means++ Clustering** and **RFM (Recency, Frequency, Monetary) Analysis**, I identified high-value "Champion" customers and at-risk segments to optimize marketing ROI.

## 🎓 Author
* **Name:** Shambhu Khanai
* **Background:** BS in Statistics and Data Science, **IIT Kanpur** (4th Semester)
* **Career Goal:** Quantitative Research (QR) / Data Science

## 🛠️ Technical Stack
* **Language:** Python 3.11
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Mathematical Techniques:** Log-Transformation, Z-Score Scaling, K-Means Clustering, Pareto Analysis

## 📈 Key Insights & Results
* **The 80/20 Rule:** Discovered that **Champions (Cluster 1)** represent only ~10% of the customer base but contribute over **60% of total revenue**.
* **Statistical Rigor:** Handled extreme skewness (**25.3**) in monetary values using `np.log1p` to ensure cluster stability.
* **Segment Strategy:** * **Champions:** VIP access & referral rewards.
    * **Loyalists:** Cross-sell & bulk-buy incentives.
    * **At-Risk:** Automated re-activation campaigns.

## 📂 Project Structure
* `notebooks/`: Contains the full end-to-end Jupyter Notebook with detailed commentary.
* `data/`: (Not uploaded due to size) Link to dataset: [UCI Online Retail II](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II)

## ⚙️ How to Run
1. Clone the repo: `git clone https://github.com/Shambhu2025/Retail-Customer-Intelligence-Engine.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook notebooks/Retail_Project.ipynb`