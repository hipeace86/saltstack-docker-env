FROM ubuntu:16.04
MAINTAINER hipeace86 <hipeace86@gmail.com>
RUN apt-get -y update && \
    apt-get install -y salt-minion vim passwd net-tools && \
    systemctl enable salt-minion && \    
    rm -rf /var/lib/apt/lists/*    
