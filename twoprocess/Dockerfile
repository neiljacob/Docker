FROM ubuntu:14.04
MAINTAINER neil "getsthomas@gmail.com"

EXPOSE 80
EXPOSE 3306

COPY run.sh run.sh
RUN chmod +x run.sh
ENTRYPOINT ["/bin/bash", "run.sh"]
