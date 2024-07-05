FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

LABEL dev.containers.features="common"

# [Optional] Uncomment this section to install additional OS packages.
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends fonts-noto-cjk texlive

