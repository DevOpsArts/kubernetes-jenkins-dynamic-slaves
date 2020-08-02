FROM jenkins/jenkins:2.235.3

#Install Plugins
COPY plugins.txt /usr/share/jenkins/ref/
RUN /usr/local/bin/install-plugins.sh < /usr/share/jenkins/ref/plugins.txt

#Volume location
VOLUME /var/jenkins

USER jenkins
