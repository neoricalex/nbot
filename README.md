# nBot
Em desenvolvimento

## Pre-Requisitos

```bash
sudo apt install postgresql postgresql-contrib
sudo apt install libpq-dev
# TODO: baseline && tensorflow
cd nbot
python -m venv env # Python 3 !
source env/bin/activate
pip install -r requerimentos.txt
```

## 

python ./src/btc/cli.py update-static-data # TODO: Bugado
python ./src/btc/cli.py --from-config config.ini optimize
