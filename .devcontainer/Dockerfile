FROM mcr.microsoft.com/vscode/devcontainers/python:3.12

# Avoid prompts during package installation
ENV DEBIAN_FRONTEND=noninteractive

# Upgrade pip and install required Python packages
RUN pip install --upgrade pip \
    && pip install \
        ipykernel \
        numpy \
    && python -m ipykernel install --sys-prefix --name devcontainer --display-name "Python 3.12 (DevContainer)"
