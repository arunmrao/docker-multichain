FROM arunmrao/base-multichain
MAINTAINER Roderik van der Veer, Arun Rao

ADD ./connect-node.sh /root/connect-node.sh

EXPOSE 7447
EXPOSE 8000

CMD ["/bin/bash", "-x", "/root/connect-node.sh"]
