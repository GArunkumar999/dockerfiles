ARG version
FROM almalinux:${version:-9}
ARG username=arun
ENV USERNAME=${username}
ARG version
RUN echo "HELLO ${username}, image version:${version}"
CMD ["sleep", "200"]