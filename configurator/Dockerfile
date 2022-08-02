ARG BUILD_FROM
FROM $BUILD_FROM

# Setup base
RUN \
    apk add --no-cache \
        git \
        openssh-client \
        python3

# Copy data
COPY rootfs /
