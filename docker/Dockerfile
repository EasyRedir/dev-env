FROM jwilder/docker-gen:latest
COPY nginx.tmpl /etc/docker-gen/templates/nginx.tmpl
COPY dhparam.pem /etc/nginx/dhparam/dhparam.pem
COPY easyredir.test.crt /etc/nginx/certs/easyredir.test.crt
COPY easyredir.test.key /etc/nginx/certs/easyredir.test.key
