plone.nginx
===========

debian based docker ct running nginx for plone

docker build -t plone.nginx

docker run --name nginx1 -d -v /home/svx/Projects/docker/plone.nginx/logs:/var/log/nginx -p 80:80 plone.nginx

you are now able to check your logs from the host system in /home/svx/Projects/docker/plone.nginx/logs
