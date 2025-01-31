FROM ubuntu
RUN apt-get update && apt-get install -y git curl && rm -rf /var/lib/apt/lists/*
USER root
COPY ../Scripting/install_awscli.sh ./opt/myfolder/
RUN apt-get clean && rm -rf /var/lib/apt/lists/* && cd /opt/myfolder/Scripting/install_awscli.sh
