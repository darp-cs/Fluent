# Fluent
FastAPI application used to transcribe and translate voice data

 ## Prerequisites
 - docker
 - python3

 ## Running the App
 1. Start the app with:
 ```bash
docker build -t fastapi-app-img .
 ```

 ```bash
docker run -d --name ml-api-service -p 8080:8080 fastapi-app-img
 ```

 2. Go to http://0.0.0.0:8080/docs.

 ## Stop the Service
 ```bash
docker stop ml-api-service
 ```