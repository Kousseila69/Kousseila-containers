FROM alpine:3.15.0
LABEL version="1.0.0" maintainer="Kousseila OUAGUENI" os="ubuntu"
RUN apt-get update
ENV CONTAINER_USER="kousseila"
RUN adduser -S -D $CONTAINER_USER
CMD ECHO "hello-alpine, I'm ,"$CONTAINER_user"and this is a container from my first image"
