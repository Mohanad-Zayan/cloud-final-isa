FROM node:16

WORKDIR /app/Products

COPY package.json .

RUN npm install

COPY . .

EXPOSE 8002

CMD ["npm","start"]



