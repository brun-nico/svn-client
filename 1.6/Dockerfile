#Retrived from : docker history --no-trunc nbrun/svn-client:1.6
FROM debian:wheezy

RUN apt-get update && apt-get install -y subversion

RUN echo "store-plaintext-passwords = no" >> /etc/subversion/servers
