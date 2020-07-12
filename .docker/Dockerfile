FROM vulnerables/web-dvwa
#enable allow_url_include
RUN sed -i'' 's/allow_url_include\s*=\s*Off/allow_url_include=On/i' /etc/php/7.0/apache2/php.ini
ENTRYPOINT ["/main.sh"]