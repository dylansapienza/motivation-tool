FROM node:14

WORKDIR /app/client

COPY package*.json ./

RUN npm install

ENV PORT = 3000

EXPOSE 3000

CMD ["npm", "start"]
