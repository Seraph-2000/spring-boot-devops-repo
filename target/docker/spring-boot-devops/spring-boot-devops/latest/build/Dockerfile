FROM quay.io/jkube/jkube-java-binary-s2i:0.0.9
ENV JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="CICD With Kubernetes" org.label-schema.version=0.0.1-SNAPSHOT org.label-schema.schema-version=1.0 org.label-schema.build-date=2022-05-17T16:23:38.376 org.label-schema.name=spring-boot-devops org.label-schema.vcs-ref=374f8b8d2c358f37c95381b56952f1f0dc01ab2b org.label-schema.vcs-url=https://github.com/krishnamurthypradeep/spring-boot-devops.git
EXPOSE 8090 8778 9779
COPY /deployments /deployments/
