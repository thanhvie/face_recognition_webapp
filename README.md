# face_recognition_webapp
## Build the Docker image
```
docker image build -t <your-image-name> .
```
## Run the container
```
docker run -p 5000:5000 -d <your-image-name>
```