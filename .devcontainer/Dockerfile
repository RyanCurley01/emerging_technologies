FROM mcr.microsoft.com/vscode/devcontainers/python:3.12

# Avoid prompts during package installation
ENV DEBIAN_FRONTEND=noninteractive

# Copy requirements file
COPY requirements.txt /tmp/requirements.txt

# Upgrade pip and install required Python packages from requirements.txt
RUN pip install --upgrade pip \
    && pip install -r /tmp/requirements.txt \
    && python -m ipykernel install --sys-prefix --name devcontainer --display-name "Python 3.12 (DevContainer)"
