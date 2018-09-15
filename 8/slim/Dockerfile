FROM node:8-slim
RUN apt-get update && apt-get install -y git zip bzip2 python --no-install-recommends \
    && rm -rf /var/lib/apt/lists/*
CMD [ "node" ]
