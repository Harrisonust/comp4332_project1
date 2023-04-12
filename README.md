# COMP4332 Project 1 (TF-IDF + various models with majority voting)

## Quickstart
Create an new conda virtual environment 
```
conda create -n comp4332_project1 python=3.10.9
conda activate comp4332_project1
```
Clone this repo and install the required packages
```
git clone git@github.com:Harrisonust/comp4332_project1.git
pip install -r requirements.txt
```
Create path for embedded features following the structure
```
/data/
    /word_embed/
        /train/
        /valid/
        /test/
```

Run notebook `main.ipynb` to train and evaluate the models.