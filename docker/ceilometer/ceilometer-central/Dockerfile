FROM kollaglue/fedora-rdo-ceilometer-base
MAINTAINER Kolla Project (https://launchpad.net/kolla)

RUN yum install -y openstack-ceilometer-central && yum clean all

ADD ./start.sh /start.sh
CMD ["/start.sh"]
