FROM node:alpine

WORKDIR /back

COPY package.json ./
RUN npm install npm && npm update npm && npm install
COPY . .
EXPOSE 9000
VOLUME /app/logs

CMD npm run dev