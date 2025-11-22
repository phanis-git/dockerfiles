FROM almalinux:9
RUN dnf install nginx -y
LABEL image_owner="phani" \
      image_consists="nginx installing"  
CMD ["nginx", "-g", "daemon off;"]