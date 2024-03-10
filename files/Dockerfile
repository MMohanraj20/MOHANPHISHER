# Dockerfile

# Author       : M.MOHANRAJ
# Github       : https://github.com/MMohanraj20
# Messenger    : https://t.me/MOhanraj43221
# Email        : MOHANRAJMOHANRAJ43221@gmail.com
# Date         : 10-03-2024
# Main Language: Python

# Download and import main images

# Operating system
FROM debian:latest
# Main package
FROM python:3

# Author info
LABEL MAINTAINER="https://github.com/MMohanraj20/MOHANPHISHER"

# Working directory
WORKDIR /MOHANPHISHER/
# Add files 
ADD . /MOHANPHISHER

# Installing other packages
RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install python3-pip php openssh-client -y
RUN pip3 install -r files/requirements.txt --break-system-packages
RUN apt-get clean

# Main command
CMD ["python3", "MOHANPHISHER.py", "--noupdate"]

## Wanna run it own? Try following commnads:

## "sudo docker build . -t M.MOHANRAJ/MOHANPHISHER:latest", "sudo docker run --rm -it M.MOHANRAJ/MOHANPHISHER:latest"

## "sudo docker pull M.MOHANRAJ/MOHANPHISHER", "sudo docker run --rm -it M.MOHANRAJ/MOHANPHISHER"
