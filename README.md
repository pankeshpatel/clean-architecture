# clean-architecture

### create a virtual environment

```python
python3 -m venv fastapienv
source fastapienv/bin/activate
deactivate 
```

### fastapi installation

```python
pip install fastapi
pip install "uvicorn[standard]"
```

### commands to run a server
- uvicorn is web-server comes with fastapi

```python
uvicorn <filename>:<fast-api-object> --reload
uvicorn books:app --reload

fastapi run books.py  # other ways to run a fastapi server
fastapi run books.py  # development mode
```