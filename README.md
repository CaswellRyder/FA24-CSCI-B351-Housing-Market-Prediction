# California Housing Market Prediction

<div align="center">

![Python](https://img.shields.io/badge/python-v3.12+-blue.svg)
![JupyterLabs](https://img.shields.io/badge/jupyterlab-4.2+-orange.svg)
![matplotlib](https://img.shields.io/badge/matplotlib-3.8+-red.svg)
![numpy](https://img.shields.io/badge/numpy-1.26+-blue.svg)
![pandas](https://img.shields.io/badge/pandas-2.1+-black.svg)
![scikit-learn](https://img.shields.io/badge/ScikitLearn-1.3+-yellow.svg)
![seaborn](https://img.shields.io/badge/seaborn-0.13+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-red.svg)

</div>

## 📋 Table of Contents
- [Overview](#overview)
- [Team](#team)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies](#technologies)
- [Training Data](#training-data)
- [Sources](#sources)
- [License](#license)

## Overview
The Housing Market Prediction project leverages machine learning to estimate the current and future value of homes based on address data, with a focus on the Bloomington, Indiana housing market. This project uses data preprocessing, feature engineering, and prediction models to achieve accurate results.

## Team
| Name | Email | GitHub |
|------|-------|---------|
| Ryder Caswell | [rcaswel@iu.edu](mailto:rcaswel@iu.edu) | [@CaswellRyder](https://github.com/CaswellRyder) |
| Anshu Roja Selvamani | [arojasel@iu.edu](mailto:arojasel@iu.edu) | [@arojasel](https://github.com/arojasel) |
| Sid Ghantasala | [sghantas@iu.edu](mailto:sghantas@iu.edu) | [@SidVeins2027](https://github.com/SidVeins2027) |

## Features
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

## Technologies

```python
# Core Dependencies
jupyterlab==4.2.6
matplotlib==3.8.1
numpy==1.26.1
pandas==2.1.3
scikit-learn==1.3.2
seaborn==0.13.0
```

## Training Data
- Link: [https://www.kaggle.com/datasets/camnugent/california-housing-prices](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
- This data set is 20,000+ entries of data on the California housing market.  
- This data set is an extensive repository of over 20,000+ data entries, offering valuable insights into the California housing market. Compiled with meticulous care, it serves as a comprehensive resource for researchers, analysts, and professionals in the real estate industry.
- Encompassing a wide range of variables, this data set provides detailed information on latitude, longitude, housing median age, total bedrooms, population, households, median income, median house value, ocean proximity. 

## Sources

- [Neural Networks in Real Estate](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4413863)
- [Machine Learning in Housing Market](https://www.sciencedirect.com/science/article/pii/S1877050920316318)
- [https://www.geeksforgeeks.org/ml-linear-regression/](https://www.geeksforgeeks.org/ml-linear-regression/)
- [https://www.geeksforgeeks.org/random-forest-regression-in-python/](https://www.geeksforgeeks.org/random-forest-regression-in-python/)
- [https://cs50.harvard.edu/ai/2024/weeks/4/](https://cs50.harvard.edu/ai/2024/weeks/4/)
- [https://www.geeksforgeeks.org/what-are-the-advantages-and-disadvantages-of-random-forest/](https://www.geeksforgeeks.org/what-are-the-advantages-and-disadvantages-of-random-forest/)
- [https://corporatefinanceinstitute.com/resources/data-science/bagging-bootstrap-aggregation/](https://corporatefinanceinstitute.com/resources/data-science/bagging-bootstrap-aggregation/)
- [https://en.wikipedia.org/wiki/Bayesian_linear_regression](https://en.wikipedia.org/wiki/Bayesian\_linear\_regression)
- [https://en.wikipedia.org/wiki/Random_forest](https://en.wikipedia.org/wiki/Random\_forest)
- [https://www.geeksforgeeks.org/decision-tree/](https://www.geeksforgeeks.org/decision-tree/)

### Code:

- [https://pandas.pydata.org/docs/reference/index.html#api](https://pandas.pydata.org/docs/reference/index.html\#api)
- [https://numpy.org/doc/stable/user/index.html#user](https://numpy.org/doc/stable/user/index.html\#user)
- [https://numpy.org/doc/stable/reference/index.html#reference](https://numpy.org/doc/stable/reference/index.html\#reference)
- [https://seaborn.pydata.org/api.html](https://seaborn.pydata.org/api.html)
- [https://seaborn.pydata.org/tutorial.html](https://seaborn.pydata.org/tutorial.html)
- [https://seaborn.pydata.org/examples/index.html#](https://seaborn.pydata.org/examples/index.html\#)
- [https://matplotlib.org/stable/users/index.html](https://matplotlib.org/stable/users/index.html)
- [https://matplotlib.org/stable/tutorials/index.html](https://matplotlib.org/stable/tutorials/index.html)
- [https://matplotlib.org/stable/api/index.html](https://matplotlib.org/stable/api/index.html)

### Data

- [https://www.kaggle.com/datasets/camnugent/california-housing-prices](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

## License

This project is by Ryder, Sid, and Anshu at Indiana University. All rights reserved by Persons. This Project and it developers **DOES NOT** give consent to be used as LLM or any other AI training data. 
All other Legal other than the afore mentioned will be based off of the [MIT License](https://opensource.org/licenses/MIT)

---

<div align="center">
Made with ☕️ at Indiana University
</div>
