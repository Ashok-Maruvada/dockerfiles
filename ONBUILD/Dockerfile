FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD [ "nginx","-g","daemon off;" ]

# Im the owner of this image and pushing the image to dockerhub as ONBUILD:V1.0
# make sure the testing user have index.html file in their workspace otherwise it will throw error