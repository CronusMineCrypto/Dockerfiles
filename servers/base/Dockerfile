FROM  ghcr.io/pterodactyl/yolks:java_17

USER  root
RUN apt install awscli -y

USER  container
COPY  ./files/entrypoint.sh /entrypoint.sh
