FROM node:17.3.1
ENV NODE_ENV=production
WORKDIR /app
COPY ["./package.json", "./package-lock.json*", "./"]
RUN npm install --production
COPY . .
ENTRYPOINT ["node", "./server.js"]