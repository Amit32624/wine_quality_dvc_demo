create env
```
conda create -n wineq python=3.8 -y
```

activate env
```
bash conda activate wineq
```

Create req file
```bash
pip install -r requirements.txt
```

git init


dvc init


dvc add data_given/winequality.csv

git add .

git commit -m "Commmit message"

TOX 
``bash
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
create an artifacts folder for mlflow
--
mlflow server
--backend-store-uri sqlite:///mlflow.db
--default-artifact-root ./artifacts
--host 0.0.0.0 -p 1234