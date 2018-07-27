FROM ubuntu
  
RUN apt-get update

RUN apt-get install -y npm

RUN npm install -g @rafaelrinaldi/whereami

ENTRYPOINT node /usr/local/bin/whereami --f human
