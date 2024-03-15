# PYTHON NO LINUX

## INSTALAÇÃO

* NO LINUX:
  
```bash
sudo apt install python-is-python3
sudo apt install python3-pip
```

## CONFIGURANÇÃO DE UM AMBIENTE VIRTUAL

```bash
sudo apt install python3.10-venv ## PACOTE NECESSÁRIO
python -m venv .venv ## CREATE
source .venv/bin/activate ## ACTIVATE
```

## INSTALAÇÃO DE PACOTES

```bash
pip install matplotlib
pip install pandas
python -m pip install pandas-stubs # TYPES FOR pandas
pip install seaborn
pip install types-seaborn # TYPES FOR seaborn
pip install plotly
pip install -U kaleido # EXPORT plotly CHARTS
pip install tabulate # REQUIRED TO CONVERT DATAFRAMES TO MARKDOWN TABLES
pip install stemgraphic # STEM AND LEAF PLOTS
```

## EXTENSÕES PARA VSCODE

* [MYPY TYPE CHECKER](https://marketplace.visualstudio.com/items?itemName=ms-python.mypy-type-checker)

## GERENCIAR REQUISITOS (VERSÕES EXATAS DE PACOTES)

* BACKUP:

  ```bash
  pip freeze > requirements.txt
  ```

* RESTAURAÇÃO:

  ```bash
  pip install -r requirements.txt
  ```

## LISTAR PACOTES INSTALADOS

  ```bash
  pip list
  ```
