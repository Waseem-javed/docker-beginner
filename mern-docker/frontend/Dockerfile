FROM node:20-alpine

USER app
WORKDIR /app
COPY package*.json ./

RUN npm install
COPY . .
EXPOSE 5173
CMD npm run dev