FROM nginx:latest

COPY nginx.conf /etc/nginx/nginx.conf
COPY ssl_params.conf /etc/nginx/ssl_params.conf

COPY ssl/shaldnikita.ru.crt /etc/nginx/shaldnikita.ru.crt
COPY ssl/shaldnikita.ru.key /etc/nginx/shaldnikita.ru.key
