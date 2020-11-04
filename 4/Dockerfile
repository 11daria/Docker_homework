# set base image
FROM python:latest

# set the working directory in the container
WORKDIR /flask

# copy the dependencies file to the working directory
COPY ./app.py .

# copy the dependencies file to the working directory
COPY ./index.html ./templates/

# install dependencies
RUN pip install flask

# ports
EXPOSE 5000

# command to run on container start
CMD [ "python", "./app.py" ]

#sudo docker run -it --rm -p 5000:5000 python
#Running on http://0.0.0.0:5000/
