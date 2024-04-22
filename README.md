# Challenge-1
## Team Members
- Elia Porter
- Raisha Rawal
- Kerek Spinney

## Project Overview
This repository contains the source code and data analysis for Challenge 1. The project is based on Jupyter notebooks and uses various Python libraries to perform data manipulation and visualization. The data we analyzed contains the results for the Financial Well-Being survey and can be found in data.gov

[Financial Well-Being in America - 2017 - Data](https://catalog.data.gov/dataset/financial-well-being-in-america-2017)

[Financial Well-Being in America - 2017 - DataSet User Guide](https://www.consumerfinance.gov/documents/5588/cfpb_nfwbs-puf-user-guide.pdf)

## Summary of the Analysis
Our analysis sought to identify variables with a moderate to strong correlation to financial well-being. While our initial hypothesis considered a broad set of factors, the results highlighted that the most significant correlations were not universally spread across all anticipated areas. Notably, financial skills, the ability to navigate life’s shocks, and maintaining savings underscored their importance to financial well-being. On the other hand, the impact of having children, frugality, and self-control, while relevant, did not exhibit as robust a correlation as expected.

The analysis underscores the importance of financial buffer—having accessible funds for unexpected needs correlates positively with financial well-being, underscoring its significance for peace of mind. Conversely, the pressure of non-essential spending is highlighted by the pronounced negative correlation seen with financial strain from gift-giving. These findings reveal a nuanced financial landscape where stability and discretionary spending have substantial but opposing effects on an individual's financial health.


## Prerequisites
Before you can run the Jupyter notebooks in this repository, you'll need to have Python installed on your system. You can download Python [here](https://www.python.org/downloads/). Additionally, ensure that `pip` is installed with Python for managing packages.

## Pre-Installation
1. Make sure your GitHub account and computer are properly configured. For detailed instructions, refer to GitHub's official documentation on setting up your account and authenticating. [GitHub Setup Documentation](https://docs.github.com/en/get-started/quickstart/set-up-git)

2. Clone this project locally, if you haven't done so already. To do this, from the command line, go to the folder where you want the local copy and run:
```shell
git clone git@github.com:kerekspinney/Project-1.git
```

## Installation
To get started with this project, you'll need to install several Python packages. Run the following commands in your terminal to install the necessary packages:

```shell
pip install pandas
pip install numpy
pip install matplotlib
pip install scipy
```
## Opening the Jupyter Notebook from VS Code
To open and run Jupyter notebooks in VS Code, you first need to install the Python extension for VS Code and configure it to recognize your Python interpreter. For detailed instructions on how to set up your environment, see the VS Code documentation on working with Jupyter notebooks: [Working with Jupyter Notebooks in VS Code](https://code.visualstudio.com/docs/python/jupyter-support)

## Opening the Jupyter Notebook using Jupyter server
To view and run the Jupyter notebook, follow these steps:

1. Ensure that Jupyter is installed. If Jupyter is not installed, you can install it using:
```shell
pip install jupyter
```
2. Navigate to the project directory where the project_code.ipynb file is located.
3. Run the following command to start Jupyter Notebook:
```shell
jupyter notebook
```
4. Jupyter will start in your default web browser. The notebook interface will show all files in the directory. Click on project_code.ipynb to open the notebook.
5. You can run the notebook cells one at a time by selecting each and pressing Shift + Enter, or you can run all cells in sequence by selecting "Run All" from the "Cell" menu.


## Contributing
We welcome contributions to this project. If you have suggestions or improvements, please fork the repository and submit a pull request.

## License
This project is licensed under MIT License.
