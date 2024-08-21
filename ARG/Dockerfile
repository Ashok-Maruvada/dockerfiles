ARG version
FROM almalinux:${version:-8}
# here giving default version as 8 if nothing passed in runtime
ARG course=docker
ARG duration=120h
RUN echo 'hi, this is ${course} with ${duration}'
CMD [ "sleep", "60" ]