#FROM nginx
#COPY default.conf /etc/nginx/conf.d/default.conf



#FROM nginx:alpine
#COPY default.conf /etc/nginx/conf.d/default.conf
#EXPOSE 80
#EXPOSE 443
#CMD [ "nginx", "-g", "daemon off;" ]

FROM nginx:alpine
COPY index.html /usr/share/nginx/html/index.html
COPY default.conf /etc/nginx/conf.d/default.conf

