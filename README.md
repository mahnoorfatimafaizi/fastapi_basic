# Steps

## Create a new project 
poetry new fastapi_01

## Change directory
cd fastapi_01

## Open Vs Code 
code .

## Download packages 
poetry add fastapi 
poetry add "uvicorn[standard]"
poetry add pytest
poetry add fastapi httpx


## Actice Env in main.py
poetry shell 


## Run
poetry run uvicorn fastapi_01.main:app --reload
 http://127.0.0.1:8000

## Test
poetry run pytest -v 

 





