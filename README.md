# poetry_setup

## --install

```
(Invoke-WebRequest -Uri https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py -UseBasicParsing).Content | python

```

#### --install dependencies

` poetry add django `


#### --activate venv 
`` poetry shell ``

#### --deactivate venv
` exit `

#### -- create venv in project folder
`poetry config virtualenvs.in-project true`
