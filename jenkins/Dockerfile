FROM jenkins/jenkins:lts
# if we want to install via apt
USER root
RUN apt-get update -y
RUN apt-get install -y vim
RUN apt-get install -y make
RUN apt-get install -y g++
# drop back to the regular jenkins user - good practice
USER jenkins

