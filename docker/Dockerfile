FROM ghcr.io/actions/actions-runner:latest

USER root
RUN apt-get update \
    && apt-get install -y \
        python3.12 python3.12-venv \
        wget ccache cmake git git-lfs \
    && rm -rf /var/lib/apt/lists/*

USER runner

ENV DEBIAN_FRONTEND=noninteractive

