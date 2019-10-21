FROM debian
USER root
RUN apt-get update && apt-get install -y sudo 
ADD . /workspace
WORKDIR /workspace
RUN chmod +x install.sh && ./install.sh