FROM zabbix/zabbix-server-pgsql:alpine-7.0-latest

USER root
# Parche de seguridad para actualizar zlib a la version 1.3.2-r1 y mitigar vulnerabilidad de overflow
RUN apk update && apk add --no-cache zlib>=1.3.2-r1

USER zabbix