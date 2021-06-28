FROM node:lts-alpine
EXPOSE 8080
WORKDIR /srv/app
COPY package.json .
RUN npm install
CMD ["npx", "http-server"]
