FROM almalinux:9
RUN dnf install nginx -y
COPY naresh.txt /tmp 
CMD ["nginx", "-g", "daemon off;"]
