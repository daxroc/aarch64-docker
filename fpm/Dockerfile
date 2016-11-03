FROM dcroche/aarch64.ruby

MAINTAINER Damien Roche

RUN gem install fpm
RUN apt-get update && \
    apt-get install -y binutils

WORKDIR /data

CMD ["bash"]
