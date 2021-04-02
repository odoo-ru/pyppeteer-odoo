Pyppeteer for Odoo
=============================
[![PyPI](https://img.shields.io/pypi/pyversions/pyppeteer-odoo.svg)](https://pypi.org/project/pyppeteer-odoo/ "Latest version on PyPI")
[![Travis](https://travis-ci.com/odoo-ru/pyppeteer-odoo.svg?branch=master)](https://travis-ci.com/odoo-ru/pyppeteer-odoo "Travis CI")
[![Docs](https://readthedocs.org/projects/pyppeteer-odoo/badge/?version=stable)](https://pyppeteer-odoo.readthedocs.io/en/latest/ "Read the docs")
[![codecov](https://codecov.io/gh/odoo-ru/pyppeteer-odoo/branch/master/graph/badge.svg)](https://codecov.io/gh/odoo-ru/pyppeteer-odoo "Coverage")

Odoo E2E Testing Helper for Pyppeteer

Install
-------
```commandline
pip install pyppeteer_odoo
```

Development
-----------
We need installed `pyenv` and `pipenv`.
```console
git clone git@github.com:odoo-ru/pyppeteer-odoo.git

cd pyppeteer-odoo
pipenv install --dev
```

Run tests:
```console
pipenv run fulltest
```
