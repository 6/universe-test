## first-time setup

Prerequisites (OS X):

- Install command-line tools with `xcode-select --install`
- Install [`brew`](http://brew.sh/)
- Install pip with `sudo easy_install pip`
- Install [docker](https://docs.docker.com/docker-for-mac/)

Set up environment:

```
cd path/to/repo
virtualenv venv
. venv/bin/activate
```

Install dependencies:

```
pip install -r requirements.txt
brew install golang libjpeg-turbo
```

## usage

Ensure that docker is running. Next, run the following in your terminal:

```
cd path/to/repo
. venv/bin/activate
python run.py
```
