FROM node:8-slim
RUN apt-get update && apt-get install -y git zip bzip2 python \
    libappindicator1 fonts-liberation libasound2 libgconf-2-4 libnspr4 libxss1 libnss3 xdg-utils \
    --no-install-recommends \
    && rm -rf /var/lib/apt/lists/*
RUN wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb && dpkg -i google-chrome*.deb && apt-get -f install && rm -f google-chrome*.deb
CMD [ "node" ]
