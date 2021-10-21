# TD Pandas
This repo contains all starting files for TD Pandas prepared by Capgemini Invent®. The dataset used for this TD is Opérations coordonnées par les CROSS.
https://www.data.gouv.fr/en/datasets/operations-coordonnees-par-les-cross/

## Clone this repository
- Clone or download this repository to start working
    - Via ssh
    ```
    git clone git@gitlab.com:centralesupelec_ds/td_pandas.git
    ```

    - Via https
    ```
    git clone https://gitlab.com/centralesupelec_ds/td_pandas.git
    ```

## Installation
### Anaconda
- Anaconda installation (you may skip this if you already have anaconda installed)
    - For window : https://docs.anaconda.com/anaconda/install/windows/
    - For MAC : https://docs.anaconda.com/anaconda/install/mac-os/

- Go to path
    ```
    cd /path/to/td_pandas
    ```
### Virtual Environment
- Create a virtual environment (you may skip this step if you already have pandas, numpy, matplotlib, seaborn and sklearn installed in your machine)
    - Using virtualenv
    ```
    virtualenv -p python3.7 venv_cs
    ```

    - Using conda
    ```
    conda create -n venv_cs python=3.7
    ```

- Activate virtual environment
    - Using virtualenv
    ```
    . venv_cs/bin/activate
    ```

    - Using conda
    ```
    conda activate venv_cs
    ```

- Install requirements
```
python -m pip install -r requirements.txt
```

## Adding virtualenv to jupyter notebook

- Open jupyter notebook
```
(venv_cs)$ jupyter notebook
```

- Add kernel to jupyter
```
(venv_cs)$ ipython kernel install --name venv_cs --user
```

## Project Organization
```
├── README.md           <- Contains description of the project
├── requirements.txt    <- required packages
├── data                <- data folder
    ├── flotteurs.csv
    ├── operations_stats.csv
    ├── operations.csv
    ├── resultats_humain.csv
    ├── train_index.json
    ├── test_index.json
├── TD CROSS.ipynb      <- notebook workbook
```