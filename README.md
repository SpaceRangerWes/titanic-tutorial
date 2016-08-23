# titanic-tutorial

## Let's Start
Before you begin with Kaggle, it is a good idea to get used to some Machine Learning (ML), Python, library, and Kaggle operations. We will be using Python (hopefully of the Python34 or higher flavor) and Apache Spark. Because the simple databricks platform is not available unless we pay for it, I will be analyzing the cost of forcing Apache Spark on the whole team. It is absolutely essential that you understand how to use Python, Jupyter, and Pandas DataFrames.

https://www.kaggle.com/c/titanic/details/getting-started-with-python is a great place to start learning how we can put it all together. Read up on the tutorial and Random Forests and try to implement your own version in either Pandas or Apache Spark.

## What To Do
Create a Jupyter notebook of your own in master with a unique name so that our seperate notebooks can be identified. Then follow the installation guide below.

### Installation with Anaconda:
1. Clone the Repo
2. Install [Anaconda](https://www.continuum.io/downloads).
3. Navigate to the directory where you unzipped or cloned the repo and use [conda](http://conda.pydata.org/docs/_downloads/conda-pip-virtualenv-translator.html) instead of pip and virtualenv.

### Installation without Anaconda:
1. Clone the Repo
2. Install [virtualenv](http://virtualenv.readthedocs.org/en/latest/installation.html).
3. Navigate to the directory where you unzipped or cloned the repo and create a virtual environment with `virtualenv env`.
4. Activate the environment with `source env/bin/activate`
5. Install the required dependencies with `pip install -r requirements.txt`.

#### Dependencies for Vanilla Python:
* [NumPy](http://www.numpy.org/)
* [jupyter notebooks](http://jupyter.org/)
* [Pandas](http://pandas.pydata.org/)
* [SciKit-Learn](http://scikit-learn.org/stable/)
* [SciPy](http://www.scipy.org/)
* [StatsModels](http://statsmodels.sourceforge.net/)
* [Matplotlib](http://matplotlib.org/)

## Interested in Apache Spark instead of Pandas?
Good news. I'm building out the titanic tutorial using Spark 1.6. Just follow this [link](http://spacerangerwes.github.io/titanic_tutorial_spark16.html) for a nice little walkthrough and try loading the included Jupyter notebook to your Databricks online notebook.
