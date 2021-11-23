### BUILD IMAGE
```
docker build --tag python-docker .
```
### RUN DOCKER
```
docker run -d -p 80:80 python-docker
```
### ACCESS PYTHON
```
curl http://localhost
```
