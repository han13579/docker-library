FROM gcr.io/spinnaker-marketplace/halyard:1.32.0
MAINTAINER yxf788@gmail.com
RUN nohup /opt/halyard/bin/halyard >> /tmp/spin.log \
    && sleep 61 \
	&& hal -v \ 
    && hal version list \
    && hal version bom 1.24.1 -q -o yaml >  1.24.1.yml