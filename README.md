![Header](header.png)

# sweetPotato

![](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)

A recipe manager built with ReactJS and Flask

## Installation

```
git clone https://github.com/Lanseuo/sweetPotato
cd sweetPotato
pip install -r requirements.txt
python3 run.py build
```

## Usage

run sweetPotato for development

```
python3 run.py
```

## Deployment

install sweetPotato permanentely (on a server)

[DEPLOYMENT.md](https://github.com/Lanseuo/sweetPotato/blob/master/DEPLOYMENT.md)

## Update

```
cd sweetPotato
. venv/bin/activate
git pull
python3 run.py build
```

on a server you have to restart supervisor too

```
supervisorctl restart sweetpotato
```

## Made with

- [Flask](http://flask.pocoo.org) - web framework
- [Flask-RESTful](https://flask-restful.readthedocs.io) - support for quickly building REST APIs
- [Flask-SQLAlchemy](http://flask-sqlalchemy.pocoo.org) - database toolkit
- [ReactJS](https://reactjs.org) - library for building user interfaces
- [axios](https://github.com/axios/axios) - HTTP client
- [Radium](https://formidable.com/open-source/radium) - tool to manage inline styles

## Meta

Lucas Hild - [https://lucas-hild.de](https://lucas-hild.de)  
This project is licensed under the MIT License - see the LICENSE file for details
