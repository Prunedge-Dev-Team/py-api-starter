# Create a .env file by copying the .env.sample

# Setup project, Create a virtual env 
```shell
git clone repo_name
cd repo_name
py -m venv venv 
source venv/bin/activate # command may be different on windows --> .\venv\Scripts\Activate.bat 
pip install poetry
poetry install
```

## run `docker-compose build`

## run `docker-compose up`

Access the doc on

```
localhost:8000/api/v1/doc
```

