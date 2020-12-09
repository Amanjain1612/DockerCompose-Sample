FROM nginx:1.13

ADD nginx.conf /etc/nginx/nginx.conf
RUN apt-get update
RUN apt-get install -y  vim curl net-tools

CMD ["nginx", "-g", "daemon off;"]
