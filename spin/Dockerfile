FROM jdehx5qv.mirror.aliyuncs.com/library/ubuntu:18.04
MAINTAINER yxf788@gmail.com
ADD InstallHalyard.sh /
RUN chmod +x /InstallHalyard.sh \
    && sudo bash InstallHalyard.sh --user runner -y \
	&& sleep 5 \
	&& hal -v 
RUN hal version list \
    && hal version bom 1.24.1 -q -o yaml >  1.24.1.yml

