# centos-ruby:extended
#
# Extended 'centos-ruby' image which allows developers to compile
# C extensioned rubygems and provide header files.
#

FROM mfojtik/centos-ruby:base
MAINTAINER Michal Fojtik <mfojtik@redhat.com>

RUN yum install --assumeyes gcc automake autoconf curl-devel openssl-devel \
      zlib-devel libxslt-devel libxml2-devel \
      mysql-libs mysql-devel \
      postgresql-devel && yum clean all