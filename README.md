# parallel
install parallel in centos 

#!/bin/bash

# Install GNU parallel on CentOS 6.

# http://software.opensuse.org//download.html?project=home%3Atange&package=parallel
cd /etc/yum.repos.d/
wget http://download.opensuse.org/repositories/home:tange/CentOS_CentOS-6/home:tange.repo
yum install parallel

# Alternative:
# yum install http://download.opensuse.org/repositories/home:/tange/CentOS_CentOS-6/noarch/parallel-20170322-1.1.noarch.rpm
