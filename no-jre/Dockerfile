FROM registry.access.redhat.com/ubi8-minimal:8.0

LABEL BASE_IMAGE="registry.access.redhat.com/ubi8-minimal:8.0"
LABEL GRAALVM_VERSION="19.0.2"

ADD libcrypt.so.2.0.0 /usr/lib64/libcrypt.so.2.0.0
RUN ln -s /usr/lib64/libcrypt.so.2.0.0 /usr/lib64/libcrypt.so.2

ADD libsunec.so /lib
