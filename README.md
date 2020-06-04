# jupyter_scikit_tensorflow_docker

## Build image docker
docker build -f Dockerfile -t tfcontainer .

## Run container
docker run -it -p 8888:8888 -d -v <path>/sources:/sources -v <path>/notebooks:/notebooks tfcontainer

go to localhost:8888 

## Sources

this is the folder where you put files like csv.