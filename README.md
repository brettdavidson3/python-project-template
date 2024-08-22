# Python Project Template

## Requirements

 - [pyenv](https://github.com/pyenv/pyenv?tab=readme-ov-file#installation)
 - [direnv](https://direnv.net/docs/installation.html)

 ## Initialize Project

```zsh
pyenv install 3.12.5
cd python-project-template
direnv allow
pip install -r requirements.txt
```

## Commands

### Install all requirements

```zsh
pip install -r requirements.txt
```

### Install new requirement

```zsh
pip install [name]
pip freeze > requirements.txt # save back to requirements.txt
direnv reload
```

### Run Tests

```zsh
pytest
```

### Run Main
```zsh
python -m main
```