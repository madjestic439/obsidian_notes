# In [[ubuntu]]
## Can be necessary
```
export PYTHON_KEYRING_BACKEND=keyring.backends.null.Keyring
```

## project creation
```
poetry new my_project
cd my_project
poetry add fastapi
poetry add uvicorn
poetry install
```
