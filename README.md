Generate Self signed certificate
openssl req -x509 -days 365 -nodes -newkey rsa:2048 -keyout /etc/nginx/ssl/self.key -out /etc/nginx/ssl/self.crt
