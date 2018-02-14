# fpf-data-tutorial
Python Data Analysis Tutorial for Freedom of the Press Foundation

## Setup

If you use `mkvirtualenv`:

```
mkvirtualenv --python=python3 fpfdata
pip install -r requirements.txt
```

If you do not use `mkvirtualenv`:

```
pip install -r requirements.txt
```

## Display notebook editor

```
jupyter notebook
```

## Display slides

```
jupyter nbconvert DataAnalysis101.ipynb --to slides --post serve
```
