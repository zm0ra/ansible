FROM alpine:latest
RUN apk add --no-cache ansible
WORKDIR k8s
COPY hosts /k8s/hosts
COPY install-k8s.yml /k8s/install-k8s.yml
