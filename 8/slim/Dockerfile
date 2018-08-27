FROM node:8-slim
RUN apt-get update && apt-get install -y git zip python python2 --no-install-recommends \
    && rm -rf /var/lib/apt/lists/*
CMD [ "node" ]
