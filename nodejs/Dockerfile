FROM node:alpine
ENV NPM_CONFIG_PREFIX=/home/node/.npm-global
ENV PATH=$PATH:/home/node/.npm-global/bin
WORKDIR /home/node/
RUN npm install progress inquirer
RUN mkdir app
USER node
