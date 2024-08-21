ARG version
FROM almalinux:${version:-8}
# here giving default version as 8 if nothing passed in runtime
ARG course=docker
ARG duration=120h
ENV COUR=${course}
RUN echo 'hi, this is ${COUR}} with ${duration}'
CMD [ "sleep", "60" ]