FROM gcr.io/spinnaker-marketplace/halyard:1.32.0
MAINTAINER yxf788@gmail.com
RUN hal -v \
    && sleep 61 \
    && hal version list \
    && hal version bom 1.24.1 -q -o yaml >  1.24.1.yml