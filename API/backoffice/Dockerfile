FROM node:alpine

WORKDIR /backoffice

COPY ./package.json ./
RUN npm install

COPY . .
EXPOSE 5173
VOLUME /app/logs

CMD npm run dev