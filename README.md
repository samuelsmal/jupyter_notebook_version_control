# Jupyter Notebooks Version Control

## Setup

To do the `.ipynb -> .py` step automatically run the following:

```
cat ./jupyter_notebook_config.py >> `jupyter --config`/jupyter_notebook_config.py
```

## From `.ipynb` to `.py`

```
python notebook_v4_to_py.py -f notebook_filename.ipynb
```

## From `.py` to `.ipynb`

```
python py_to_notebook_v4.py -f py_filename.py
```

## Additional Stuff

You can "activate" an automatic git commit. Have a look into the
`jupyter_notebook_config.py` file. In the `post_save` method at the end of the
file just uncomment the code.

