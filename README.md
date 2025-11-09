# ML Portfolio

A collection of machine learning projects and experiments.

## Project Structure

```
ML_Portfolio/
├── venv/                    # Virtual environment (not committed to git)
├── notebooks/               # Jupyter notebooks for experiments
├── src/                     # Production Python scripts
├── data/                    # Datasets (not committed to git)
├── models/                  # Saved models (not committed to git)
├── requirements.txt         # Python dependencies
└── README.md               # This file
```

## Setup

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd ML_Portfolio
```

### 2. Create and activate virtual environment
```bash
# Create virtual environment
python3 -m venv venv

# Activate it
source venv/bin/activate  # On Mac/Linux
# venv\Scripts\activate   # On Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Start Jupyter
```bash
jupyter notebook
# Or just open .ipynb files directly in Cursor!
```

## Usage in Cursor

1. Open the ML_Portfolio folder in Cursor
2. Open any `.ipynb` file from the `notebooks/` folder
3. Run cells directly in Cursor (no need for Jupyter Lab!)
4. Make sure to activate the virtual environment in the terminal:
   ```bash
   source venv/bin/activate
   ```

## Projects

- **01-linear-regression/**: Linear regression experiments
- **sample_ml_model.ipynb**: Random Forest classifier example

## Contributing

Feel free to add your own projects to this portfolio!

## License

MIT

