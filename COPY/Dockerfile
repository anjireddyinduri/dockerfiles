FROM almalinux:9
RUN /bin/sh -c dnf install  sivanji1979/accuknoxns/ngnix:latest -y 
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]
