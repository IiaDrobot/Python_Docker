FROM node:18-slim

LABEL authors="Iia Drobot"

WORKDIR /my_app

COPY . .

RUN npm install --only=production

CMD ["npm", "start"]