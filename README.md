# doa18
doa18 stuff

wget --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u131-b11/d54c1d3a095b4ff2b6607d096fa80163/jdk-8u131-linux-x64.rpm

sudo rpm –Uvh jdk-8u131-linux-x64.rpm

sudo su

alternatives --install /usr/bin/java java /usr/java/latest/bin/java 200000

alternatives --install /usr/bin/javac javac /usr/java/latest/bin/javac 200000

alternatives --install /usr/bin/jar jar /usr/java/latest/bin/jar 200000

