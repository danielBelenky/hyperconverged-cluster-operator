FROM centos:centos8.1.1911

COPY deploy/nightly-bundle/deploy.sh /deploy.sh
COPY deploy/nightly-bundle/create_docker_config.sh /create_docker_config.sh

RUN dnf install -y jq
RUN chmod +x /deploy.sh /create_docker_config.sh
