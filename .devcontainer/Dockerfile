FROM mcr.microsoft.com/vscode/devcontainers/python:3.11
WORKDIR /app
COPY ./requirements.txt /app
RUN apt-get update && \
    apt-get install -y graphviz && \
    pip install -r requirements.txt
