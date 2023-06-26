# Learning Models
TH Rosenheim   
06/29/2023  

This Jupyter Notebook is based on Harvards CS109 Data Science 2015 lecture "Learning Models": http://cs109.github.io/2015/pages/videos.html  

## Setup
To set up your python environment and to run the code in this repository, follow the instructions below.

1. Download Conda

1. Create (and activate) a new environment with Python 3.6.

	```bash
	conda create --name learningmodels python=3.6
	conda activate learningmodels
	```

1. Install Jupyter

    ```bash
	conda install jupyter
	```

1. Download repository
    ```bash
    cd path/to/folder
    git clone https://github.com/clauszitzelsberger/LearningModels.git
    ```

1. Install python libraries
    ```
    cd LearningModels
    pip install -r requirements.txt
    ```

1. Launch Jupyter Notebook
    ```
    jupyter notebook
    ```

1. Launch Presentation
    ```
    jupyter nbconvert LearningModels.ipynb --to slides --post serve
    ```
