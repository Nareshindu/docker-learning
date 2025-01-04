FROM almalinux:9
RUN dnf install nginx -y
ADD https://github.com/Nareshindu/docker-learning /tmp
ADD monitoring.log-20241201.gz /tmp
CMD ["nginx", "-g", "daemon off;"]