FROM almalinux:9
RUN dnf install nginx -y
copy naresh.txt /tmp 
CMD ["nginx", "-g", "daemon off;"]
