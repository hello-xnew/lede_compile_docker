FROM ubuntu:20.04


#apt 相关设置非交互模式
RUN apt-get update \
    && DEBIAN_FRONTEND=noninteractive apt-get install -y --no-install-recommends \
    build-essential asciidoc binutils bzip2 gawk gettext git libncurses5-dev libz-dev patch python3 python2.7 unzip \
    zlib1g-dev lib32gcc1 libc6-dev-i386 subversion flex uglifyjs git-core gcc-multilib p7zip p7zip-full msmtp \
    libssl-dev texinfo libglib2.0-dev xmlto qemu-utils upx libelf-dev autoconf automake libtool autopoint \
    device-tree-compiler g++-multilib antlr3 gperf wget curl swig rsync \
	&& apt-get clean

#user
RUN /usr/sbin/useradd new && mkdir "/home/new"


CMD while :;echo hello; do sleep 10000;done