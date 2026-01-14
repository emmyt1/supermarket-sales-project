# 🛒 Supermarket Sales Prediction & Business Insights

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Gradient%20Boosting-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 Project Overview
A comprehensive data science project analyzing supermarket transaction data to build predictive models for total sales and extract actionable business insights for operational optimization.

**Key Achievement**: Despite discovering the dataset's synthetic nature (perfect mathematical relationships), successfully pivoted to deliver valuable business intelligence and built robust predictive models achieving 98.9% accuracy on realistic data.

## 🎯 Business Objectives
- Predict total sales per transaction for inventory planning
- Identify patterns affecting sales performance
- Provide actionable recommendations for supermarket management
- Optimize staffing and inventory strategies

## 📊 Dataset
- **Source**: [Kaggle Supermarket Sales Dataset](https://www.kaggle.com/datasets/faresashraf1001/supermarket-sales)
- **Records**: 1,000 transactions
- **Features**: 16 variables (product, customer, temporal, payment)
- **Period**: January-March 2019

## 🛠️ Technical Implementation

### Data Processing Pipeline
1. **Data Quality Assessment**: Missing values, duplicates, outliers
2. **Feature Engineering**: Temporal features (hour, day, weekend)
3. **Data Leakage Handling**: Identified and removed synthetic relationships
4. **Encoding & Scaling**: One-hot encoding, standardization

### Model Development
- **Algorithms**: Linear Regression, Random Forest, Gradient Boosting
- **Best Model**: Gradient Boosting Regressor (R² = 0.989)
- **Hyperparameter Tuning**: GridSearchCV for optimization
- **Evaluation**: RMSE, R², MAE, MAPE metrics

## 📈 Key Results

### Model Performance
| Model | RMSE | R² Score |
|-------|------|----------|
| Gradient Boosting | $27.09 | 0.989 |
| Random Forest | $29.55 | 0.987 |
| Linear Regression | $87.70 | 0.884 |

### Business Insights
1. **Top Revenue Categories**: Food & Beverages ($56,145), Sports & Travel ($55,123)
2. **Peak Performance**: 7 PM (peak hour), Saturday (best day)
3. **Customer Behavior**: Members spend $29 more per transaction
4. **Payment Trends**: Ewallet most popular (345 transactions)

## 💡 Actionable Recommendations
1. **Inventory Focus**: Prioritize Food & Beverages and Sports & Travel (34% revenue)
2. **Staff Scheduling**: Peak hours: 7 PM, 1 PM, 3 PM
3. **Promotion Strategy**: Target Mondays (weakest performance)
4. **Loyalty Expansion**: Capitalize on higher member spending

## 🏗️ Project Structure
```supermarket-sales-prediction/
├── LICENSE/ # License page
├── README.md/ # This file
├── business_insights.png/ # Dashboard Visualization
├── requirements.txt/ # Key requirements
└── supermarket_sales_project(O.O.E)/ # Jupyter notebook with full analysis
```

## 🚀 Getting Started

### Installation
```bash
# Clone repository
git clone https://github.com/yourusername/supermarket-sales-prediction.git
cd supermarket-sales-prediction

# Install dependencies
pip install -r requirements.txt
```

## 🧠 Key Learnings
1. Data Validation: Importance of checking dataset integrity and relationships
2. Business Pivot: Adapting approach when initial assumptions prove incorrect
3. Model Interpretability: Balancing accuracy with explainability
4. Actionable Insights: Translating technical findings to business value

## 🤝 Contributing
Contributions welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author
**Oluwaseun E. Olubunmi**
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/ooluwaseun/)
- [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/emmyt1)

## 🙏 Acknowledgments
- Kaggle for the dataset
- Open-source community for Python libraries
