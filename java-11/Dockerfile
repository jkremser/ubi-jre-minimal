FROM registry.access.redhat.com/ubi8/ubi-minimal:8.0

LABEL BASE_IMAGE="registry.access.redhat.com/ubi8/ubi-minimal:8.0"
LABEL JAVA_VERSION="11"

RUN microdnf install --nodocs java-11-openjdk-headless && microdnf clean all
