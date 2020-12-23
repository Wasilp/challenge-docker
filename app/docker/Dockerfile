FROM python:3.7
RUN mkdir app
COPY . /app
RUN pip install -r app/requirements.txt
WORKDIR /app
CMD ["python", "pipeline/model/model.py"]

# from app 
#docker build . -f docker/Dockerfile -t hello_docker
## docker run -it hello_docker
# docker run -v $PWD:/app -it hello_docker bash
#docker stop $(docker ps -aq)
#docker rm $(docker ps -aq)
#docker rmi $(docker images -q)