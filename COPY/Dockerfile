FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/html.index
COPY index.html /usr/share/nginx/html/html.index
CMD ["nginx", "-g", "daemon off;"]