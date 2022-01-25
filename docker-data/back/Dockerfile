FROM node:16.13.0

RUN yarn global add tyarn \
    && tyarn global add pm2

WORKDIR /home/project

EXPOSE 3000

CMD tyarn && pm2-runtime ecosystem.config.js --env production