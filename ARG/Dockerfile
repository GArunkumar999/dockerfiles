# version will access by FROM only and upto FROM we can access this vesrion value
ARG version
FROM almalinux:${version:-9}
ARG username=arun
ENV USERNAME=${username}
# we can't access version here 
RUN echo "HELLO ${username}, image version:${version}" 
CMD ["sleep", "200"]