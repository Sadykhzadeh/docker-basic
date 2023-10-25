FROM ubuntu
RUN apt-get update && apt-get install -y netcat
CMD ["nc", "-l", "-p", "8080"]