# dockerize-nginx-as-loadbalance
dockerize nginx to proxy as loadblance 
## .$NGINX.CONF-DIR is the DIR of nginx.conf in this git repo

`docker run --name nginx-proxy -p 8080:80 -v $NGINX.CONF-DIR:/etc/nginx/conf.d -d nginx `
