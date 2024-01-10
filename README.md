## Weather Data Analysis: A Regression and Classification Approach on the ERA5 Dataset


---

### Project description

*This GitHub repository houses the code and resources for the weather prediction final project for the lecture "Data Science with Statistics 2023/24". The project focuses on analyzing atmospheric data from Bancroft, Ontario, employing regression and classification techniques to predict temperature trends and weather events. The analysis delves into the challenges and complexities inherent in meteorological studies, providing insights into the dynamic nature of weather patterns.*


---

### Getting Started 

To get started on this project, users navigate to the base path "/project" using a terminal or command prompt. Here they create a new Conda environment with Python 3.12 using the command "conda create --name proj_env  python=3.12". After activating the environment using "conda activate proj_env" the necessary modules and dependencies can be installed from the requirements.txt using the command "conda install --file requirements/requirements.txt". Now the Jupyter Notebooks can be launched using any IDE (Visual Studio Code was used in the development).

---

### Project structure



```nohighlight
├── README.md          <- The top-level README for people using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `01-JK-data-preparation.ipynb`.
│
├── references         <- Data dictionaries, project explanations, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements       <- The requirements file for reproducing the analysis environment, e.g. a `environment.yml` file

```    
