FROM ubuntu:latest
RUN \
  apt-get update && \
  apt-get -y upgrade && \
  rm -rf /var/lib/apt/lists/*
COPY ./stress.sh ./
RUN chmod +x stress.sh
CMD ["./stress.sh"]