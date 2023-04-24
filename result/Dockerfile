FROM node:12.12.0-alpine
RUN apk update && apk add npm
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 80
CMD ["node", "server.js"]