FROM ghcr.io/foundry-rs/foundry:fe2acca4e379793539db80e032d76ffe0110298b

RUN apk add jq
ADD funder.sh /
#RUN chmod a+rx /funder.sh
ENTRYPOINT  /funder.sh 
