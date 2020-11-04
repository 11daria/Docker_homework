# set base image
FROM python:3.6

# copy the dependencies file to the working directory
COPY homework-3/hits/app.py .

# copy the dependencies file to the working directory
COPY homework-3/requirements.txt .

# install dependencies
RUN pip install -r requirements.txt

#create "logs" directory
RUN mkdir logs

# ports
EXPOSE 5000

# command to run on container start
CMD [ "python", "./app.py" ]

#sudo docker run -it --rm -p 5000:5000 python
#Running on http://0.0.0.0:5000/
