FROM  nginx:alpine

LABEL autor="ARIEL"
LABEL description="Dockerfile para el curso de Docker"

COPY index.html /usr/share/nginx/html
COPY style.css /usr/share/nginx/html


EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]