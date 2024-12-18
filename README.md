# Housing Market Prediction

<div align="center">

![Python](https://img.shields.io/badge/python-v3.12+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.16+-orange.svg)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

</div>

## 📋 Table of Contents
- [Overview](#overview)
- [Team](#team)
- [Features](#features)
- [Technologies](#technologies)
- [Timeline](#timeline)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview
The Housing Market Prediction project leverages machine learning to estimate the current and future value of homes based on address data, with a focus on the Bloomington, Indiana housing market. This project uses data preprocessing, feature engineering, and prediction models to achieve accurate results.

## 👥 Team
| Name | Email | GitHub |
|------|-------|---------|
| Ryder Caswell | [rcaswel@iu.edu](mailto:rcaswel@iu.edu) | [@CaswellRyder](https://github.com/CaswellRyder) |
| Anshu Roja Selvamani | [arojasel@iu.edu](mailto:arojasel@iu.edu) | [@arojasel](https://github.com/arojasel) |
| Sid Ghantasala | [sghantas@iu.edu](mailto:sghantas@iu.edu) | [@SidVeins2027](https://github.com/SidVeins2027) |

## ✨ Features
- Data preprocessing for clean input
- Feature engineering specific to real estate data
- Model training and evaluation for price prediction
- Results visualization


## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd FA24-CSCI-B351-Housing-Market-Prediction
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate    # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. (Optional) Install Jupyter Notebook if using notebooks (You can also just use VS Code if you already have and use or prefer it.):
   ```bash
   pip install jupyter
   ```

## Usage

1. Ensure all dependencies are installed and the virtual environment is activated.
2. Prepare your dataset and place it in the `data` directory.
3. (Optional) Launch Jupyter Notebook for interactive data analysis (You can also just use VS Code if you already have and use or prefer it.):
   ```bash
   cd projectDirectory
   jupyter lab # or code . # if you have the terminal extension installed you can run it.
   ```
4. Run the python notebook in either VS Code or Jupyter Labs. The results will appear at the bottom of the notebook if ran and setup correctly.

## Project Structure

- `housing-market-model-main.ipynb`: Main Code for the project.
- `data/`: Directory for raw and processed datasets.
- `requirements.txt`: Python dependencies for the project.
- `README.md`: Documentation for the project.

## 🛠️ Technologies

```python
# Core Dependencies
jupyterlab==4.2.6
matplotlib==3.8.1
numpy==1.26.1
pandas==2.1.3
scikit-learn==1.3.2
seaborn==0.13.0
```

## 💾 Training Data
- Link: [https://www.kaggle.com/datasets/camnugent/california-housing-prices](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
- This data set is 20,000+ entries of data on the California housing market.  
- This data set is an extensive repository of over 20,000+ data entries, offering valuable insights into the California housing market. Compiled with meticulous care, it serves as a comprehensive resource for researchers, analysts, and professionals in the real estate industry.
- Encompassing a wide range of variables, this data set provides detailed information on latitude, longitude, housing median age, total bedrooms, population, households, median income, median house value, ocean proximity. 


## 📄 License

This project is by Ryder, Sid, and Anshu at Indiana University. All rights reserved by Persons. This Project and it developers **DOES NOT** give consent to be used as LLM or any other AI training data. 
[MIT License](https://opensource.org/licenses/MIT)

## 📚 References

- [Neural Networks in Real Estate](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4413863)
- [Machine Learning in Housing Market](https://www.sciencedirect.com/science/article/pii/S1877050920316318)

---

<div align="center">
Made with ❤️ at Indiana University
</div>
