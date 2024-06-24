## Deploying a model as a web-service

* Creating a virtual environment with Pipeenv
* Creating a script for prediction
* Putting the script into a Flask app
* Packaging the app to Docker


```bash
docker build -t ride-duration-prediction-service:v1 .
```


```bash
docker run -it --rm -p 9696:9696 ride-duration-prediction-service:v1
```