FROM node:22.15.1-alpine3.21

ENV PORT 80
EXPOSE 80

WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .

CMD ["npm", "start"]
