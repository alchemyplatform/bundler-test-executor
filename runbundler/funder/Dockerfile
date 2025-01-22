FROM ghcr.io/foundry-rs/foundry:latest

RUN apt-get update && apt-get install -y jq
ADD funder.sh /
#RUN chmod a+rx /funder.sh
ENTRYPOINT  /funder.sh 
