FROM mailserver/docker-mailserver:edge

RUN chmod -R 777 /var/mail/
RUN echo "TLS_REQCERT never" >> /etc/ldap/ldap.conf
#RUN echo "debug_level = 1" >> /etc/dovecot/dovecot-ldap.conf.ext