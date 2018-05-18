FROM bats-jenkins

COPY plugins.txt /usr/lib/jenkins/ref/
RUN /usr/local/bin/plugins.sh /usr/lib/jenkins/ref/plugins.txt
