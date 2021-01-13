FROM gitlab/gitlab-runner:latest
RUN apt-get update && \
    apt-get install -y yamllint && \
    rm -rf /var/lib/apt/lists/*