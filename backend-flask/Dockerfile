FROM python:3.10-slim-buster

#container abstraction - making a new folder like this inside container
WORKDIR /backend-flask

#outside the container to inside the container
COPY requirements.txt requirements.txt

# install python libraries inside the container
RUN pip3 install -r requirements.txt

# The two periods/dots means copy everything in the curr directory
COPY . .

ENV FLASK_ENV=development

EXPOSE ${PORT}

# python3 -m flask run --host=0.0.0.0 --port=4567
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]