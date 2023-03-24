FROM eclipsecbijenkins/openshift-java:jdk8u212-b04_openj9-0.14.2@sha256:1753a59d9a0cc94999bf1ecad179ab73f7b820363dac7421a56c1470d7252aa7

RUN apk add --no-cache \
  xmlstarlet

ENV HOME=/home/jenkins
WORKDIR /home/jenkins

ENTRYPOINT [ "uid_entrypoint" ]