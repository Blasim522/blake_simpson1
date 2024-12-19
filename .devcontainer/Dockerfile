FROM mcr.microsoft.com/devcontainers/universal:2-linux
# Install the xz-utils package
RUN apt-get update && apt-get install-y python3 python3-pip xz-utils && \
    apt-get clean && rm -rf /var/lib/apt/lists/*
#install Vue
RUN npm install -g @vue/cli
#install Flask
RUN pip3 install Flask

#directory
WORKDIR /workspace