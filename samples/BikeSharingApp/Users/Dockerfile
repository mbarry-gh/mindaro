FROM node:14.17.6-alpine3.11

ENV PORT 80
EXPOSE 80

WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .

CMD ["npm", "start"]