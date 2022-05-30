FROM node:16

WORKDIR /app/Shopping

COPY package.json .

RUN npm install

COPY . .

EXPOSE 8003

CMD ["npm","start"]



