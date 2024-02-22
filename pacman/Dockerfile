FROM nginx:latest

WORKDIR /home/ctw03459/Git/pacman

# COPY nginx.conf /etc/nginx/nginx.conf

COPY ./src /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]