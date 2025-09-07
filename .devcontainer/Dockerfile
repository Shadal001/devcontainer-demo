FROM FROM node:20-bookworm

# Install PostgreSQL client (so developers can test connections)
RUN apt-get update && apt-get install -y \
    postgresql-client \
    && rm -rf /var/lib/apt/lists/*

# Set working directory
WORKDIR /workspace

