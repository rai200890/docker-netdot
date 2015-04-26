#HTTPD container
###Building container:
docker build -t raissa/httpd
###Running container:
docker run -d -p 127.0.0.1:80:80 --name httpd raissa/httpd
