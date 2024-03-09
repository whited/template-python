# Python Bootstrap (Basic)

This repository is intended to be a Template for bootstrapping generic Python projects.
I wrote this to make getting started a bit quicker for myself.  Anyone is welcome to use it, but it comes with NO support.

To Setup initial python virtual env, do the following:
```bash
# create virtual environment
python -m venv .venv

# activate env
source .venv/bin/activate

# Update PIP, and install requirements
pip install --upgrade pip
pip install -r requirements.txt
```

Then start working in either:
- [main.py](src/main.py)
- [flask_main.py](src/flask_main.py)
- [notebook.ipynb](notebooks/notebook.ipynb)

## Python References
### General
- [Python.org](https://python.org/)

### HTTP Related
- [Requests](https://docs.python-requests.org/en/latest/index.html)
- [Flask Documentation](https://flask.palletsprojects.com/en/3.0.x/) -- Simple HTTP Server
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) -- HTML/XML parsing

### Data Analysis / Notebooks
- [Jupyter](https://jupyter.org/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Polars](https://pola.rs/)
- [Plotly](https://plotly.com/python-api-reference/generated/plotly.html)

### Other
- [rich](https://github.com/Textualize/rich) -- Pretty console text formatting
