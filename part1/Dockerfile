FROM ubuntu:22.04

WORKDIR /usr/src/app

COPY script.sh .

RUN apt-get update && apt-get install curl -y

RUN chmod +x script.sh

CMD [ "/bin/bash","./script.sh" ]

