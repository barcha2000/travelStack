# Travel Stack Classificator

### Overview

The project involves developing a machine learning classifier to predict whether a given question has received an accepted answer.

We will endeavor to identify an effective classifier through a comprehensive process. We will initiate with a Jupyter notebook dedicated to data preprocessing, meticulously preparing the data for analysis. Following this, we will explore and construct various classifiers, leveraging the capabilities of PySpark to manage and analyze the data efficiently. Our goal is to find a model that accurately predicts our target variable, utilizing PySpark's robust processing power to handle large datasets and complex computations.

### Data

The dataset used in this project is available on the Stack Overflow website, accessible under a license that permits its use for analysis and development purposes. Link: https://archive.org/details/stackexchange

### Requirements

Before running the project, it's essential to set up a virtual environment to manage the dependencies effectively. Ensure you have Python 3.8 installed on your system, as the source code is compatible with this version. After installing Python 3.8, create a virtual environment in your project directory. Once the virtual environment is activated, install the required packages listed in requirements.txt. This project also utilizes Apache Spark version 3.5, so make sure that Spark is installed and properly configured to work with Python 3.8 in your development environment. This setup ensures that all dependencies are managed correctly and that the project runs smoothly in an isolated environment.

### Notebook

The source code for this project is contained within the notebooks directory, provided in two formats for convenience and accessibility. The primary format is the Python Notebook format (.ipynb), which allows for interactive execution, visualization, and in-depth commentary alongside the code. For those who wish to view the content without running the code interactively, a static version in HTML format is also available, offering a straightforward way to inspect the code's functionality, output, and accompanying explanations without the need for a Jupyter environment.

### Results


In the results directory, you will find the outcomes of the classifiers' performance evaluations. The results are presented through three key statistics: accuracy, AUC (Area Under the ROC Curve), and informedness. These metrics provide a comprehensive overview of the classifiers' effectiveness, with accuracy measuring the overall correctness of predictions, AUC reflecting the model's ability to discriminate between classes, and informedness indicating the model's capability to make informed predictions beyond random guessing.
