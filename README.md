# Corona cases
This repository contains a Jupyter notebook to visualize the corona cases either per country of worldwide. The underlying data is provided by [Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19/). 

## Installation
- Follow these steps to run this Jupyter notebook within a virtual environment

```bash
# Install Jupyter notebook
pip3 install jupyter

# Install virtual environment
pip3 install virtualenv

# Create virtual environment
python3 -m venv .venv

# Activate virtual environment
source .venv/bin/activate

# Install package dependencies
pip install -r requirements.txt

# Install virtual environment as Jupyter notebook kernel
ipython kernel install --user --name=.venv

# Install widget extension to the Jupyter notebook kernel
jupyter nbextension enable --py widgetsnbextension

# Run the jupyter notebook
jupyter notebook
```

# Launch as Azure Notebooks