# titanic-tutorial

## Introduction
Before you begin with Kaggle, it is a good idea to get used to some Machine Learning (ML), Python, library, and Kaggle
operations. We will be using Python (hopefully of the Python34 or higher flavor) and Apache Spark. Because the simple
[Databricks](https://databricks.com/product/getting-started-with-apache-spark-on-databricks) platform is not available
unless we pay for it, I will be analyzing the cost of forcing Apache Spark on the whole team. It is absolutely essential
that you understand how to use Python, Jupyter, and Pandas DataFrames.

https://www.kaggle.com/c/titanic/details/getting-started-with-python is a great place to start learning how we can put
it all together. Read up on the tutorial and Random Forests and try to implement your own version in either Pandas or
Apache Spark.

## Installing Python3

### macOS

1.  Install [Homebrew](http://brew.sh/):

    ```
    $ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    ```

2.  Upgrade Homebrew:

    ```
    $ brew upgrade
    ```

3.  Install Python3:

    ```
    $ brew install python3
    ```

### Windows

Coming soon...

### Debian

Coming soon...

### Ubuntu

Coming soon...

## Setup

1.  [Setup your Github SSH keys](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/)
    if you haven't already (make sure that the correct OS is selected at the top of the article).
2.  Clone the repo:

    ```
    $ git clone git@github.com:KaggleCityMo/titanic-tutorial.git
    ```

### Installation with Anaconda:

3.  Install [Anaconda](https://www.continuum.io/downloads).
4.  Navigate into the `titanic-tutorial` repo you just cloned and active Anaconda.
    [Anaconda acts as both a package manager like pip and a virtual environment like pyvenv](http://conda.pydata.org/docs/_downloads/conda-pip-virtualenv-translator.html):

    ```
    $ conda
    ```

### Installation with pyvenv and pip:

3.  Navigate into the `titanic-tutorial` repo you just cloned and create a Python virtual environment:

    ```
    $ pyvenv venv
    ```

4.  Activate the environment:

    ```
    $ source env/bin/activate
    ```

5.  Verify that you're using Python 3:

    ```
    $ python --version
    ```
6.  Install the required dependencies:

    ```
    $ pip install -r requirements.txt
    ```

## Running the Notebook

To run the Jupyter notebook:
```
$ jupyter notebook
```

Then in your web browser, go to the `localhost:####` URL given in the Terminal output if it doesn't automatically open.

## Interested in Apache Spark instead of Pandas?

Good news. I'm building out the titanic tutorial using Spark 1.6. Just follow this
[link](http://spacerangerwes.github.io/titanic_tutorial_spark16.html) for a nice little walkthrough and try loading the
included Jupyter notebook to your Databricks online notebook.
