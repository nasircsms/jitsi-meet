FROM rocketchat/base
ENV RC_VERSION latest
MAINTAINER buildmaster@rocket.chat

RUN apt-get update && \
	apt-get install -y wget dnsutils vim telnet && \
	apt-get update && \
	apt-get clean


EXPOSE 80 443 5347
EXPOSE 10000/udp 10001/udp 10002/udp 10003/udp 10004/udp 10005/udp 10006/udp 10007/udp 10008/udp 10009/udp 10010/udp
