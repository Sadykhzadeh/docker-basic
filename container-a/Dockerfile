FROM ubuntu
RUN apt-get update && apt-get install -y netcat
CMD ["sh", "-c", "while true; do echo 'Hello from Container A' | nc container-b 8080; sleep 2; done"]