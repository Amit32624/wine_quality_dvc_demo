create env
```
conda create -n wineq python=3.8 -y
```

activate env
```
conda activate wineq
```

Create req file
```
pip install -r requirements.txt
```

git init


dvc init


dvc add data_given/winequality.csv

git add .

git commit -m "Commmit message"

TOX 
``
tox
```

for rebuilding
``` bash
tox -r
```

pytest command
``` bash
pytest -v
```
set up commands
```bash
pip install -e .
```

To build your own package commands

``` bash
python setup.py sdist bdist_wheel
```
