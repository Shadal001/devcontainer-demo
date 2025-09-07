FROM node:18-bullseye

# Install PostgreSQL client (so developers can test connections)
RUN apt-get update && apt-get install -y \
    postgresql-client \
    && rm -rf /var/lib/apt/lists/*

# Set working directory
WORKDIR /workspace

