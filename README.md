# Yml-apache-
version: '3'

services:
  apache:
    build: .
    ports:
      - "80:80"
    volumes:
      - ./index.html:/usr/local/apache2/htdocs/index.html
      
