## Setup

### Setup Virtual Env

```bash
python -m venv my-venv
```

### Use pip-tools to Generate requirements.txt

- `python -m pip install pip-tools`
- Create file requirements.in
- `pip-compile requirements.in`


### Install Requirements

`pip install -r requirements.txt`

### Juypter Start

`python -m ipykernel install --user --name=my-venv --display-name "Python (my-venv)"`
`jupyter notebook`
or `jupyter lab`
