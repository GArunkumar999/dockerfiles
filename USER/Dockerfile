FROM almalinux:9
# expense user is not able to craete files 
RUN useradd expense 
# arun user is not able to craete files 
RUN useradd arun 
USER arun
CMD ["sleep", "100"]
# root user only create file by default in container 
RUN echo "HELLO WORLD" > file.txt
RUN chmod +w file.txt
