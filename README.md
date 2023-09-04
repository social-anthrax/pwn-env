# Pwn-Env

A poetry environment containing a bunch of libraries for pwn/rev and the like (a little web as a treat).

Runs on both x86 and arm machines (Tested on x86 ubuntu and M1 Mac).

## Requirements

- At least python11
- [Poetry](https://python-poetry.org/docs/#installation)

## Included packages

- pwntools
- angr
- monkeyhex
- ipython
- ipykernel

### Optional under the data_analysis group

- pandas
- tabulate

## Installation

```bash
poetry install 
# alternatively with data analysis packages such as pandas
poetry install --with data_analysis

# Open the shell
poetry shell
```
