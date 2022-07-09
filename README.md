create env 
```bash
conda create -n wineq python=3.7 -y
```
activate env 
```bash
conda activate wineq
```
create a req file and install
```bash 
pip install -r requirements.txt
```
git init
dvc init
dvc add data_givem/winequality.csv

git add .
git commit -m "First commit"

