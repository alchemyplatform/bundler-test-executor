FROM ghcr.io/foundry-rs/foundry@sha256:09143a1c5ad22ae6b5fbb3d9ac39a5e0cff6be425836e4f1715dc0e204f9899f

RUN apk add jq
ADD funder.sh /
#RUN chmod a+rx /funder.sh
ENTRYPOINT  /funder.sh 
