FROM node:alpine
WORKDIR /api-back
COPY package.json ./
RUN npm install
COPY . .
EXPOSE 9000
VOLUME /app/logs

CMD npm run dev