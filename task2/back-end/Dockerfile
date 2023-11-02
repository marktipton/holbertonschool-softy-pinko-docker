# Latest ubuntu
FROM ubuntu:latest

# Update APT repo
RUN apt-get update

# Upgrade APT
RUN apt-get upgrade -y

RUN apt-get install -y python3 python3-pip

RUN pip3 install Flask

WORKDIR /app

COPY ./api.py /app/api.py

EXPOSE 5252

# Set command to run when the container starts
CMD ["python3", "api.py"]