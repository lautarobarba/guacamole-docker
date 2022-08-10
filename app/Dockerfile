# Produccion
FROM ubuntu:20.04 AS production

WORKDIR /app/guacamole

# Instalo dependencias
RUN apt -y update
# RUN apt install --yes build-essential libcairo2-dev libjpeg-turbo8-dev \
RUN apt install --yes build-essential libcairo2-dev libjpeg-turbo8-dev \
    # libpng-dev libtool-bin libossp-uuid-dev libvncserver-dev \
    # freerdp2-dev libssh2-1-dev libtelnet-dev libwebsockets-dev \
    # libpulse-dev libvorbis-dev libwebp-dev libssl-dev \
    # libpango1.0-dev libswscale-dev libavcodec-dev libavutil-dev \
    # libavformat-dev wget tar nginx curl vim nmap

# Instalo guacamole server
# RUN wget https://downloads.apache.org/guacamole/1.4.0/source/guacamole-server-1.4.0.tar.gz
# RUN tar -xvf guacamole-server-1.4.0.tar.gz
# RUN cd guacamole-server-1.4.0
# RUN sh configure --with-init-dir=/etc/init.d --enable-allow-freerdp-snapshots
# RUN make
# RUN make install
# RUN ldconfig
# RUN mkdir -p /etc/guacamole/{extensions,lib}

# Instalo guacamole web app
# RUN apt -y install tomcat9 tomcat9-admin tomcat9-common tomcat9-user
# RUN wget https://downloads.apache.org/guacamole/1.3.0/binary/guacamole-1.3.0.war
# RUN mv guacamole-1.3.0.war /var/lib/tomcat9/webapps/guacamole.war
