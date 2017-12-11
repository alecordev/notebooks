# Jupyter / ipython Notebooks

Example notebooks.

## Command line

- `jupyter notebook --generate-config`

Usual options that need tweaking:

- `iopub_data_rate_limit`
- Create a password hash to write it in the config file: 
    1. `jupyter notebook password`
    2. `c.NotebookApp.password`
- `c.NotebookApp.ip = '*'`
- `c.NotebookApp.open_browser = False`
- `c.NotebookApp.port = 9999`

## Jupyter Notebook Docs

- http://jupyter-notebook.readthedocs.io/en/stable/notebook.html

## Useful Resources

- https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/