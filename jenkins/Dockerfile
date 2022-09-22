FROM jenkins/jenkins:2.361.1-jdk11
COPY --chown=jenkins:jenkins plugins /home/plugins
COPY jenkins.sh /usr/local/bin
ENV JAVA_TOOL_OPTIONS="-Dhudson.model.UpdateCenter.never=true"
