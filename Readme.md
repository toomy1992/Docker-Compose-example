# Cerficate generate by

openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout  key.key -out  cert.crt -subj '/CN=localhost'

openssl dhparam -out dhparam.pem 2048
