FROM alpine:latest
RUN apk add --no-cache ansible
WORKDIR k8s
COPY . /
COPY ./ssh /root/.ssh/
