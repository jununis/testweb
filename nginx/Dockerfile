FROM nginx

LABEL maintainer="Your Name <your.email@example.com>"
ENV ENVIRONMENT=production

COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
