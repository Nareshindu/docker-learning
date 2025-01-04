FROM almalinux:9
RUN dnf install nginx -y
COPY naresh.tt /tmp 
CMD ["nginx", "-g", "daemon off;"]
