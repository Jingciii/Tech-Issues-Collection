# Tech-Issues-Collection

## Virtual Env

**Issue**: Sys path inconsistent in notebooks

**Des**: Cannot import installed packages inside jupyter notebook --> cannot find venv in sys.path/sys.executable

**Sol**: 

*jupyter/ipykernel not installed in venv*
```
pip install ipython
```
```
pip install jupyter
```
```
pip install ipykernel
```
check
```
jupyter kernelspec list
```

*Still not fix:*
```
ipython kernel install --user --name=VENV_NAME
```
see details [here](https://stackoverflow.com/questions/42449814/running-jupyter-notebook-in-a-virtualenv-installed-sklearn-module-not-available)
