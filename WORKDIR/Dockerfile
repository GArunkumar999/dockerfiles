FROM almalinux:latest
RUN mkdir /tmp/test
WORKDIR /tmp/test
#cd command won't work in docker we have to use WORKDIR instruction to change directory
#RUN cd /tmp/test (won't work)
RUN pwd
CMD ["sleep", "200"]