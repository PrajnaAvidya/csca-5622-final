# Wine Quality Prediction

## Overview

This is my final project for CSCA 5622 at CU Boulder. I tried to predict the quality of Portugese Vinho Verde wines using their chemical properties.  The dataset used for this project is the Wine Quality Dataset:
```
  P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.
  Modeling wine preferences by data mining from physicochemical properties.
  In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.

  Available at: [@Elsevier] http://dx.doi.org/10.1016/j.dss.2009.05.016
                [Pre-press (pdf)] http://www3.dsi.uminho.pt/pcortez/winequality09.pdf
                [bib] http://www3.dsi.uminho.pt/pcortez/dss09.bib
```

## Structure

- `linear-regression.ipynb`: A Jupyter notebook that demonstrates exploratory data analysis and implements multiple linear regression and lasso regression models.
- `random-forest-gradient-boost.ipynb`: Another notebook that implements random forest and gradient boosting regression models.
- `requirements.txt`: The required Python packages to run the notebooks.

## How to Run

1. **Clone the repository**:

    ```bash
    git clone git@github.com:PrajnaAvidya/csca-5622-final.git
    ```

2. **Create a virtual environment**:

    ```bash
    python -m venv .venv
    source venv/bin/activate
    ```

3. **Install packages**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the notebooks**:

    There's a few different ways to do this. Some IDEs like PyCharm run Jupyter notebooks automatically, but you could also use docker to spin JupyterLab, or just install it locally. You can also review the contents/results of the notebooks on the GitHub website without having to run it locally.