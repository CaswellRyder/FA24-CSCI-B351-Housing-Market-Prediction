
# Housing Market Prediction

## Overview
The Housing Market Prediction project leverages machine learning to estimate the current and future value of homes based on address data, with a focus on the Bloomington, Indiana housing market. This project uses data preprocessing, feature engineering, and prediction models to achieve accurate results.

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

4. (Optional) Install Jupyter Notebook if using notebooks:
   ```bash
   pip install jupyter
   ```

## Usage

1. Ensure all dependencies are installed and the virtual environment is activated.
2. Prepare your dataset and place it in the `data` directory.
3. Run the main script for training and predictions:
   ```bash
   python main.py
   ```
4. (Optional) Launch Jupyter Notebook for interactive data analysis:
   ```bash
   jupyter notebook
   ```

## Project Structure

- `main.py`: Entry point for the project.
- `data/`: Directory for raw and processed datasets.
- `requirements.txt`: Python dependencies for the project.
- `README.md`: Documentation for the project.

## Contributing
Contributions are welcome! Please create a pull request with detailed descriptions of your changes.

## License
[MIT License](https://opensource.org/licenses/MIT)
