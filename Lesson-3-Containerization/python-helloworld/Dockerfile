FROM python:3.8
LABEL maintainer="Udacity"

WORKDIR /app
COPY . /app

RUN pip install --upgrade pip
RUN pip install -r requirements.txt

EXPOSE 80

# command to run on container start
CMD [ "python", "app.py" ]
