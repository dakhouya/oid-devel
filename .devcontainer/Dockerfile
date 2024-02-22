FROM mcr.microsoft.com/devcontainers/base:jammy

# Development tools
RUN apt update && apt install -y --no-install-recommends \
    build-essential \
    cmake \
    gdb-multiarch \
    libopencv-dev \
    ninja-build \
    python3-opencv \
    # Cleanup
    && rm -rf /var/lib/apt/lists/*

# Oid requirements
RUN apt update && apt install -y --no-install-recommends \
    libpython3-dev \
    libx11-xcb-dev \
    libglu1-mesa-dev \
    libglib2.0-dev \
    libfontconfig1 \
    libqt5opengl5-dev \
    libxrender-dev \
    libxkbcommon-x11-0 \
    libdbus-1-3 \
    python3-dev \
    qtbase5-dev \
    # Cleanup
    && rm -rf /var/lib/apt/lists/*
