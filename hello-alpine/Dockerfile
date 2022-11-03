FROM alpine:3.15.0
LABEL version="1.0.0" maintainer="Kousseila OUAGUENI" os="ubuntu"
ENV CONTAINER_USER "kousseila"
RUN adduser -S -D $CONTAINER_USER
USER $CONTAINER_USER
CMD echo  "hello-alpine, $CONTAINER_USER  and this is a container from my first image"
