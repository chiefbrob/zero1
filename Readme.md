# Python 101 (Python 3)

[Tutorial](https://code.visualstudio.com/docs/python/python-tutorial)

Checking version installed

```bash
python3 --version
```

Select a Python 3 interpreter by opening the Command Palette (⇧⌘P), start typing the Python: Select Interpreter command to search, then select the command.

Right click and select run python from terminal

Initialize the debugger, press F5

## Create and activate the virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
```

## Select your new environment (⇧⌘P) Python: Select Interpreter

should have ('.venv': venv)

### macOS

```bash
python3 -m pip install matplotlib
```

### Linux (Debian)

```bash
apt-get install python3-tk

python3 -m pip install matplotlib
```

## Save requirements

```bash
pip freeze > requirements.txt
```

## load requirements

```bash
pip install -r requirements.txt
```

## Type deactivate

Exits virtual env
