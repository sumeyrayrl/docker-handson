FROM ubuntu
RUN apt-get update -y
RUN apt-get install python3 -y
RUN apt-get install python3-pip -y
RUN pip3 install Flask --break-system-packages
COPY . /app
WORKDIR /app
CMD python3 ./welcome.py