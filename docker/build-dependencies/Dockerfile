FROM ubuntu:bionic

ENV DEBIAN_FRONTEND noninteractive

RUN \
	apt-get update && \
	apt-get install -y wget apt-utils lsb-release build-essential libbz2-dev automake libtool-bin libssl1.0-dev

RUN \
	mkdir -p /src && \
	cd /src && \
	wget http://sourceforge.net/projects/boost/files/boost/1.58.0/boost_1_58_0.tar.gz && \
	tar -xzvkf boost_1_58_0.tar.gz && \
	wget https://github.com/libevent/libevent/archive/release-2.0.22-stable.tar.gz && \
	tar -xzvkf release-2.0.22-stable.tar.gz  

RUN \
	cd /src/boost_1_58_0 && \
	./bootstrap.sh --prefix=/equibit && \
	./b2 variant=release link=shared --without-python --without-mpi -q install

RUN \
	cd /src/libevent-release-2.0.22-stable && \
	./autogen.sh && \
	./configure --prefix=/equibit && \
	make && \
	make install
