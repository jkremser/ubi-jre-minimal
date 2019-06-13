FROM registry.access.redhat.com/ubi8/ubi-minimal:8.0

LABEL BASE_IMAGE="registry.access.redhat.com/ubi8/ubi-minimal:8.0"
LABEL JAVA_VERSION="1.8"

RUN microdnf install --nodocs java-1.8.0-openjdk-headless && microdnf clean all
