FROM node:8-slim
RUN apt-get update && apt-get install -y git zip bzip2 python libxcomposite1:amd64 libx11-6:amd64 libx11-xcb-dev:amd64 --no-install-recommends \
    && rm -rf /var/lib/apt/lists/*
CMD [ "node" ]
