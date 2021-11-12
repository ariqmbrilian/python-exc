# Learn-Python

## DEPLOY PYTHON WITHOUT CONTAINER
### INSTALL PACKAGES
```
pip3 install Flask
pip3 freeze | grep Flask >> requirements.txt
```
### START APPLICATION
```
python3 -m flask run
```
### ACCESS WITH ANOTHER CONNECTION ON
```
curl localhost:5000
```

## DEPLOY PYTHON WITH CONTAINER
### BUILD IMAGE
```
docker build --tag python-docker .
```
### RUN DOCKER
```
docker run -d -p 5000:5000 python-docker
```