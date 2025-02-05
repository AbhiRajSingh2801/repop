FROM ubuntu
RUN apt-get update && apt-get install -y git curl && rm -rf /var/lib/apt/lists/*
USER root
WORKDIR /app
COPY ../Scripting/Test/Copy.sh /app/
RUN apt-get clean && rm -rf /var/lib/apt/lists/* && cd /etc/os-releases && cd /Users/abhisheksinghkushwah/Desktop/Learning_Coding/Scripting/install_awscli.sh