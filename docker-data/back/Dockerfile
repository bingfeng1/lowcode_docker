FROM node:16

RUN yarn global add tyarn \
    && tyarn global add pm2

WORKDIR /home/project

EXPOSE 3000

CMD ["pm2-runtime","ecosystem.config.js"]