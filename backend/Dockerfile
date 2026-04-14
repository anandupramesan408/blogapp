FROM node:21
WORKDIR /app
COPY package*.json ./
RUN npm ci --omit=dev
COPY . .
#COPY  .env.docker .env
EXPOSE 5000
CMD [ "npm","start" ]