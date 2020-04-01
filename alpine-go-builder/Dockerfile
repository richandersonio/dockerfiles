FROM alpine AS core

RUN apk --update add git less openssh

RUN apk add bash
RUN apk add go

# clean anu apk files not needed

RUN rm -rf /var/lib/apt/lists/* && \
    rm /var/cache/apk/*

CMD ["/bin/bash"]

#=======================End of layer: al2_v3  =================