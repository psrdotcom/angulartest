FROM nginx:1.21.0-alpine
COPY nginx.conf /etc/nginx/nginx.conf
COPY certificate.crt /etc/nginx
COPY private.key /etc/nginx
COPY /dist /usr/share/nginx/html
EXPOSE 443