# Python Syntax

## Download
- install package:
brew install pyenv

- setup shell:
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zshrc
echo 'command -v pyenv >/dev/null || export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(pyenv init -)"' >> ~/.zshrc

source ~/.zshrc

- check:
pyenv --version

## Quản lý python version
- install python version
pyenv install <python_version>

- versions đã tải
pyenv versions

- set global version
pyenv global
pyenv global <version>

- set local version
pyenv local
pyenv local <version>

## Workflow: pyenv + venv
- set local version:
pyenv local <version>

- create virtual environment
python -m venv .venv

- activate
source .venv/bin/activate

- install necessary packages
pip install numpy pandas

- freeze dependencies
pip freeze > requirements.txt

- deactivate
