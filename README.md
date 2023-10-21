
# NLP 201 - n-gram language modeling



## Introduction

The goal of this Project is to train a model to tag slots in natural language utterances of users addressing a virtual personal assistant. 


## Requirements

The project uses [Python 3.10](https://www.python.org/downloads) which has some linting defaults which may cause import
errors if using python < 3.10.

The requirements can be installed using the following command:

```bash
    # create a virtual environment
    py -m venv env
    env\Scripts\activate
    
    # install requirements
    pip install -r requirements.txt
```


## Running the code

The code has been written in jupyter notebook so that each part can be run individually and test different senarios and variables along the way. The notebook can also be imported into colab as well if you prefer working in the cloud GPU.



## Project Structure

The project is structured as follows:

```bash
    .
    ├── data
    │   ├── 1b_benchmark.dev.tokens
    │   ├── 1b_benchmark.test.tokens
    │   ├── 1b_benchmark.train.tokens
    │   └── preprocessed.train.tokens (you can generate this again if you want)
    ├── README.md
    ├── requirements.txt
    ├── Report.pdf
    └── ngram_modeling.ipynb
```

The `data` folder contains the data files for the project. The `notebook` is a jupyter notebook which contains the code
for the project. 


## Authors

Parsa Mazaheri, November 2022