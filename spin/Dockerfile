FROM gcr.io/spinnaker-marketplace/halyard:1.32.0
MAINTAINER yxf788@gmail.com

RUN /opt/halyard/bin/halyard >> /tmp/a &

RUN ps -ef; \ 
    sleep 0; \
	ps -ef; \ 
    hal version list; \
    hal version bom 1.24.1 -q -o yaml >  ~/1.24.1.yml

