FROM      busybox:latest

# Copy testrun.sh files into the container

ADD	./testrun.sh       /tmp/
ADD ./oldFile.txt 	   /

RUN mkdir -p /usr/local/bin
RUN cp /tmp/testrun.sh /usr/local/bin/ && chmod +x /usr/local/bin/testrun.sh

CMD ["testrun.sh"]
