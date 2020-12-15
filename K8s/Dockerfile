FROM jenkins/jenkins:lts

# Plugins for better UX (not mandatory)
RUN /usr/local/bin/install-plugins.sh ansicolor
RUN /usr/local/bin/install-plugins.sh greenballs

# Plugin for scaling Jenkins agents
RUN /usr/local/bin/install-plugins.sh kubernetes

RUN /usr/local/bin/install-plugins.sh workflow-aggregator ant nodejs sonar blueocean gradle git htmlpublisher slack

USER jenkins
