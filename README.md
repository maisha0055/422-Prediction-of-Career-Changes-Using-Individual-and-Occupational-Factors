# Prediction of Career Changes Using Individual and Occupational Factors

## Overview

This project develops a machine learning model to predict the likelihood of career changes based on individual characteristics and occupational factors. By analyzing demographic, educational, and professional attributes, the model provides insights into career transition patterns and identifies key drivers of career mobility.

## Project Objectives

- **Predict Career Transitions**: Build a classification model to forecast whether an individual will change careers
- **Identify Key Factors**: Determine which individual and occupational variables most significantly influence career changes
- **Risk Assessment**: Provide stakeholders with evidence-based metrics for understanding career mobility
- **Data-Driven Insights**: Enable organizations to better understand workforce dynamics and retention factors

## Methodology

### Data Source & Features
The analysis incorporates individual and occupational factors including:
- **Individual Factors**: Demographics, education level, experience, age, and personal characteristics
- **Occupational Factors**: Industry, job role, salary, job satisfaction, and market conditions

### Model Architecture
- **Algorithm**: Supervised classification approach
- **Validation Strategy**: Cross-validation with train-test split
- **Performance Metrics**: Accuracy, Precision, Recall, and F1-Score

### Model Performance
- **Accuracy**: **85.6%**
- **Framework**: Machine learning with ensemble techniques
- **Tools**: Python, scikit-learn, and data analysis libraries

## Repository Structure

```
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_feature_engineering.ipynb
│   └── 04_model_training_evaluation.ipynb
├── data/
│   ├── raw/
│   └── processed/
├── src/
│   └── utils.py
├── README.md
└── requirements.txt
```

## Installation & Setup

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- pip package manager

### Dependencies
```bash
pip install -r requirements.txt
```

**Key Libraries:**
- pandas (data manipulation)
- numpy (numerical computing)
- scikit-learn (machine learning)
- matplotlib & seaborn (visualization)
- jupyter (interactive notebooks)

## Usage

1. **Clone the Repository**
   ```bash
   git clone https://github.com/maisha0055/422-Prediction-of-Career-Changes-Using-Individual-and-Occupational-Factors.git
   cd 422-Prediction-of-Career-Changes-Using-Individual-and-Occupational-Factors
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Analysis**
   - Launch Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Execute notebooks in sequential order starting with `01_data_exploration.ipynb`
   - Follow the documented workflow for data processing, feature engineering, and model training

4. **Review Results**
   - Model evaluation metrics and visualizations are generated in the final notebook
   - Feature importance rankings identify top predictors of career changes

## Key Findings

- The model achieves **85.6% accuracy** in predicting career changes
- [Primary factors influencing career transitions are identified through feature importance analysis]
- [Career mobility patterns vary significantly across different occupational sectors]
- [Individual satisfaction and market conditions emerge as critical predictors]

## Technologies Used

![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.7+-blue?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-green?style=flat-square)
![pandas](https://img.shields.io/badge/pandas-Data-yellow?style=flat-square)

## Project Composition
- **Jupyter Notebooks**: 98.1%
- **Python Scripts**: 1.9%

## Results & Interpretation

The classification model demonstrates strong predictive performance with an accuracy of **85.6%**. This indicates that the selected individual and occupational features effectively capture career change dynamics. The model can be utilized for:

- **HR Analytics**: Identifying high-risk employees likely to transition careers
- **Retention Strategy**: Developing targeted interventions for career development
- **Workforce Planning**: Forecasting potential workforce changes
- **Career Counseling**: Assisting individuals in understanding their career trajectory risks

## Limitations & Future Work

### Current Limitations
- Model performance may vary across different demographic groups
- Historical data may not fully capture emerging market trends
- External factors (economic conditions, policy changes) require separate analysis

### Future Enhancements
- Incorporate real-time labor market data
- Develop segmented models for specific industries
- Implement deep learning approaches for improved accuracy
- Create interactive dashboard for stakeholder access

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## License

This project is available under the MIT License. See LICENSE file for details.

## Contact & Support

For questions, suggestions, or collaboration opportunities:
- **GitHub**: [@maisha0055](https://github.com/maisha0055)
- **Email**: [Your contact information]

---

**Last Updated**: August 2026  
**Project Status**: Completed ✓