FROM almalinux:9
RUN dnf install nginx -y
#RUN /bin/sh -c dnf install  sivanji1979/accuknoxns/ngnix:latest -y 
#RUN rm -rf /usr/share/nginx/html/index.html
#COPY index.html /usr/share/nginx/html/index.html
#CMD ["sleep","10000"]
CMD ["nginx","-g","daemon off;"]
