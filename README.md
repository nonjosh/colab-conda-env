# Exported conda/pip list from Google Colab
<p>Tensorflow 1.15.0 and 2.0.0 available. (both GPU version)</p>
The folder `colab/` contains `requirement.txt` export by running `pip freeze > requirements.txt` in Colab.



## Import
```sh
# conda
conda env create -f environment.yml

# pip
pip install -r requirements.txt
```

## Export
```sh
# conda
conda env export > environment.yml

# pip
pip freeze > requirements.txt
```