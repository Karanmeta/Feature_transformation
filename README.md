# Feature Transformation

A comprehensive collection of feature engineering and data preprocessing techniques implemented in Jupyter notebooks. This repository contains practical examples and implementations of various data transformation methods commonly used in machine learning and data science projects.

## 🎯 Overview

This repository demonstrates different approaches to feature transformation, data preprocessing, and handling various data quality issues. Each notebook focuses on specific techniques with real-world datasets to provide hands-on learning experience.

## 📁 Repository Structure

### 📓 Jupyter Notebooks

| Notebook | Description |
|----------|-------------|
| `IQR.ipynb` | Interquartile Range method for outlier detection and handling |
| `KNN_imputer.ipynb` | K-Nearest Neighbors imputation for missing values |
| `Z_score.ipynb` | Z-score standardization and outlier detection |
| `automatically-select-imputer-parameters.ipynb` | Automated parameter selection for imputation methods |
| `categorical.ipynb` | Categorical data encoding techniques |
| `handling_date.ipynb` | Date and time feature engineering |
| `handling_missing.ipynb` | Comprehensive missing data handling strategies |
| `missing_indicator.ipynb` | Missing value indicators and feature creation |
| `mixval.ipynb` | Mixed value type handling and preprocessing |
| `percentile.ipynb` | Percentile-based transformations and scaling |
| `random_indicator.ipynb` | Random missing data indicators |
| `step-by-step.ipynb` | Step-by-step feature transformation pipeline |

### 📊 Datasets

| Dataset | Description |
|---------|-------------|
| `50_Startups.csv` | Startup company data for regression analysis |
| `data_science_job.csv` | Data science job market data |
| `house-train.csv` | Housing data for price prediction |
| `messages.csv` | Text message data for classification |
| `orders.csv` | E-commerce order data |
| `placement.csv` | Student placement data |
| `titanic.csv` | Famous Titanic survival dataset |
| `train.csv` | General training dataset |
| `traink.csv` | Training dataset with some missing values |
| `trains.csv` | Training dataset variant outliers |
| `weight-height.csv` | Weight and height measurements |

## 🔧 Features Covered

### Data Preprocessing
- **Missing Value Handling**: Multiple imputation strategies including KNN, mean/median/mode imputation
- **Outlier Detection**: IQR method, Z-score analysis, and percentile-based approaches
- **Data Type Handling**: Mixed value types, categorical encoding, date/time processing

### Feature Engineering
- **Scaling & Normalization**: Z-score standardization, percentile transformations
- **Categorical Encoding**: Various encoding techniques for categorical variables
- **Feature Creation**: Missing indicators, derived features from dates
- **Pipeline Development**: Step-by-step transformation workflows

### Advanced Techniques
- **Automated Parameter Selection**: Smart parameter tuning for imputation methods
- **Missing Data Indicators**: Creating features from missing value patterns
- **Date Feature Engineering**: Extracting temporal features from date columns

## 🚀 Getting Started

### Prerequisites
```python
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
```

### Installation
1. Clone the repository:
```bash
git clone https://github.com/Karanmeta/Feature_transformation.git
cd Feature_transformation
```

2. Install required packages:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

## 📈 Usage Examples

### Basic Missing Value Imputation
```python
# Load the KNN imputer notebook for practical examples
# of handling missing values using K-Nearest Neighbors
```

### Outlier Detection
```python
# Check IQR.ipynb for interquartile range method
# Check Z_score.ipynb for standard score outlier detection
```

### Categorical Encoding
```python
# Explore categorical.ipynb for various encoding techniques
# including one-hot encoding, label encoding, and more
```

## 🎓 Learning Path

1. **Start with**: `step-by-step.ipynb` - Get an overview of the complete pipeline
2. **Missing Data**: `handling_missing.ipynb` → `KNN_imputer.ipynb` → `missing_indicator.ipynb`
3. **Outlier Handling**: `Z_score.ipynb` → `IQR.ipynb` → `percentile.ipynb`
4. **Feature Engineering**: `categorical.ipynb` → `handling_date.ipynb` → `mixval.ipynb`
5. **Advanced Topics**: `automatically-select-imputer-parameters.ipynb` → `random_indicator.ipynb`

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Karan Mehta** - [Karanmeta](https://github.com/Karanmeta)
- LinkedIn: [Karan Mehta](https://www.linkedin.com/in/karan-mehta-492122333)

## 🙏 Acknowledgments

- Thanks to the open-source community for providing excellent datasets
- Inspired by real-world data science challenges and best practices
- Special thanks to contributors and feedback from the data science community

## 📚 Additional Resources

- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Feature Engineering Best Practices](https://developers.google.com/machine-learning/data-prep/construct/sampling-splitting/imbalanced-data)

---

⭐ Star this repository if you found it helpful!