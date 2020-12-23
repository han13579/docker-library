FROM gcr.io/spinnaker-marketplace/halyard:1.32.0
MAINTAINER yxf788@gmail.com
ADD InstallHalyard.sh /
RUN hal version list \
    && sleep 15 \
    && hal version bom 1.24.1 -q -o yaml >  1.24.1.yml

