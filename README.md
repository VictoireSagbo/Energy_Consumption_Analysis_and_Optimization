# Energy Consumption Analysis

This project aims to analyze and optimize energy consumption data for various countries using data from Kaggle. The dataset includes energy consumption information from 1900 to 2021 for different countries.

## Project Structure

- `Energy_Consumption_Analysis.ipynb`: Jupyter Notebook containing the analysis of energy consumption data.
- `energy_data_download.py`: Python script to download energy data for a specific country.

## Requirements

- Python 3.x
- pandas
- kaggle

## Setup Instructions

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/energy-consumption-analysis.git
    cd energy-consumption-analysis
    ```

2. **Install the required Python packages**:
    ```bash
    pip install pandas kaggle
    ```

3. **Set up Kaggle API credentials**:
    - Sign in to your Kaggle account.
    - Go to your account settings and create a new API token.
    - This will download a `kaggle.json` file to your computer.
    - Place the `kaggle.json` file in the `~/.kaggle/` directory (for Linux and macOS) or `C:\Users\<Your-Username>\.kaggle\` directory (for Windows).
    - Ensure the file has the correct permissions:
      ```bash
      chmod 600 ~/.kaggle/kaggle.json
      ```
