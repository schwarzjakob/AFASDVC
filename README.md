# README

## Setup Instructions

### 1. Clone the Repository
Ensure you have the repository with the Jupyter Notebook and CSV files cloned locally.

### 2. Set Up Virtual Environment
Run the following commands to set up a Python virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### 3. Install Required Packages
Install dependencies from `requirements.txt`:
```bash
pip install -r requirements.txt
```

### 4. Install Jupyter and Kernel
If Jupyter is not installed, run:
```bash
pip install jupyter
```

Add the virtual environment to Jupyter:
```bash
python -m ipykernel install --user --name=venv
```

### 5. File Setup
Manually place the provided CSV files into the `input_data/` folder within your working directory. Ensure the following files are present:

- `population absolute_clean.csv`
- `pop under 14 proportion_clean.csv`
- `pop above 80 in proportion_clean.csv`
- `pop 65-79 proportion_clean.csv`
- `pop 50-64 proportion_clean.csv`
- `pop 25-49 proportion_clean.csv`
- `pop 15-24 proportion_clean.csv`
- `net lending or borrowing_clean.csv`
- `Labor productivity_clean.csv`
- `GDP_clean.csv`
- `foreign born population_clean.csv`
- `current account balance_clean.csv`

### 6. Running the Jupyter Notebook
Run the Jupyter notebook with the following command:
```bash
jupyter notebook
```

Open the `.ipynb` file in the Jupyter interface and execute the cells sequentially.

### 7. Data Cleaning
The script automatically cleans the data by:
- Renaming columns
- Removing NaN values
- Converting data types as required

### Troubleshooting
Ensure all CSV files are correctly placed and formatted to avoid import errors. For any missing dependencies, update the `requirements.txt` accordingly.