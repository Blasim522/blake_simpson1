FROM mcr.microsoft.com/devcontainers/universal:2-linux
# Install the xz-utils package
RUN apt-get update && apt-get install
#install Vue
RUN npm install -g @vue/cli
#install Flask
RUN pip3 install Flask

#directory
WORKDIR/workspace