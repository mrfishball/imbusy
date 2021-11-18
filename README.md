# imbusy

## Requirements

- Python 3.9.7 (or the version in .python-version, whichever is higher)
- Version manager: pyenv via Homebrew
- Virtualenv

## Development
- Clone repo and cd into it
- Create a virtual environment:
```sh
python -m venv .
```
- Activate the virtual environment:
```sh
source bin/activate
```
- Install project dependenices:
```sh
pip install -r requirements.txt
```
- Prepare your `client_secret.json`:
    - Login to your Google developer console. (If you don't have an account, you'll need to create one
    and then create an app with the Calendar API enabled.)

    - Download the OAuth credential json file
    Rename it to `client_secret.json` and put it in the root directory of this project

- Run connect:
```sh
python connect.py
```
