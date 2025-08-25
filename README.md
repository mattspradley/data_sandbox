# Data Sandbox

A Jupyter notebook project for data science experiments and analysis.

## Project Structure

```text
data_sandbox/
├── notebooks/          # Jupyter notebooks
├── data/              # Data files
│   ├── raw/           # Raw, unprocessed data
│   ├── processed/     # Cleaned and processed data
│   └── external/      # External data sources
├── src/               # Python source code
├── requirements.txt   # Python dependencies
├── .gitignore        # Git ignore file
└── README.md         # This file
```

## Getting Started

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Start Jupyter Lab:

   ```bash
   jupyter lab
   ```

3. Open the notebooks in the `notebooks/` folder to begin exploring!

## Dependencies

- Python 3.8+
- Jupyter Lab
- Common data science libraries (pandas, numpy, matplotlib, seaborn, etc.)

## Usage

- Place your raw data files in `data/raw/`
- Create new notebooks in the `notebooks/` folder
- Add reusable Python functions to the `src/` folder
- Document your findings and processes in the notebooks
