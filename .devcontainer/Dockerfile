FROM mcr.microsoft.com/devcontainers/javascript-node:22-bookworm

# Install additional development tools
RUN apt-get update && apt-get install -y \
    build-essential \
    pkg-config \
    python3 \
    && rm -rf /var/lib/apt/lists/*

# Enable pnpm
RUN corepack enable pnpm

USER node
