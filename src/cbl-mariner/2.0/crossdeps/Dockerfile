FROM mcr.microsoft.com/cbl-mariner/base/core:2.0

RUN tdnf update -y && \
    tdnf install -y \
        # Provides 'su', required by Azure DevOps
        util-linux \
        wget \
        ca-certificates \
        git \
        # Common runtime build dependencies
        cmake \
        awk \
        icu \
        tar \
        diffutils \
        # Crosscomponents build dependencies
        glibc-devel \
        lttng-ust-devel \
        kernel-headers \
        # Jit rolling build dependency
        python3-pip
