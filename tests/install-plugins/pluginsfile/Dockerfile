FROM bats-jenkins

COPY plugins.txt /usr/lib/jenkins/ref/plugins.txt
RUN /usr/local/bin/install-plugins.sh < /usr/lib/jenkins/ref/plugins.txt
