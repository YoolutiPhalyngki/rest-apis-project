# CONTRIBUTING

## How to run the Dockerfile locally

### In Linux or Ubuntu system:
```
docker run -dp 5000:5000 -w /app -v "$(pwd):/app" IMAGE_NAME sh -c "flask run"
```

### In Windows:
```
docker run -dp 5000:5000 -w //app -v "//c/Users/yooluti/Program Exe/PythonFlask_rest_api://app" rest-apis-flask-python
```