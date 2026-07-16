FROM ubuntu:24.04
RUN apt-get update && apt-get install -y cowsay
COPY message.txt /tmp/message.txt
CMD ["sh", "-c", "/usr/games/cowsay $(cat /tmp/message.txt)"]

