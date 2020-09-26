FROM nginx:1.19.2

#RUN apk add --update nginx && rm -rf /var/cache/apk/*

#COPY nginx.conf /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf
#COPY index.html /var/www/html/index.html
COPY index.html /usr/share/nginx/html/index.html

CMD ["nginx", "-g", " daemon off;"]

