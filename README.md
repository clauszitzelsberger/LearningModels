# Learning Models
TH Rosenheim  
11/23/2022  

## Steps to launch the Jupyter Notebook
To set up your python environment to run the code in this repository, follow the instructions below.

1. Download Conda

1. Create (and activate) a new environment with Python 3.6.

	```bash
	conda create --name name python=3.6
	conda activate name
	```

1. Install Jupyter

    ```bash
	conda install jupyter
	```

1. Download repository
    ```bash
    cd path/to/directory
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