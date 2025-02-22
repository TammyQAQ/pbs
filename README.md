# Proposer Builder Separation

[![python](https://img.shields.io/badge/Python-v3.11.3-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![build status](https://github.com/pre-commit/pre-commit/actions/workflows/main.yml/badge.svg)](https://github.com/xujiahuayz/pbs/actions/workflows/pylint.yml)

## Setup

```
git clone https://github.com/xujiahuayz/pbs.git
cd pbs
```

### Give execute permission to your script and then run `setup_repo.sh`

```
chmod +x setup_repo.sh
./setup_repo.sh
. venv/bin/activate
```

or follow the step-by-step instructions below between the two horizontal rules:

---

#### Create a python virtual environment

- MacOS / Linux

```bash
python3 -m venv venv
```

- Windows

```bash
python -m venv venv
```

#### Activate the virtual environment

- MacOS / Linux

```bash
. venv/bin/activate
```

- Windows (in Command Prompt, NOT Powershell)

```bash
venv\Scripts\activate.bat
```
#### Install toml

```
pip install toml
```

#### Install the project in editable mode

```bash
pip install -e ".[dev]"
```

#### Install pre-commit
```bash
pre-commit install
```
