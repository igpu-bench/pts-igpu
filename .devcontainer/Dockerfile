ARG VARIANT=ubuntu-22.04
FROM mcr.microsoft.com/vscode/devcontainers/base:0-${VARIANT}


RUN apt-get update && apt-get install -y --no-install-recommends \
  php-cli \
  php-xml \
  && rm -rf /var/lib/apt/lists/*
