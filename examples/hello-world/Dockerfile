FROM node:18-alpine
WORKDIR /app
COPY package*.json /app/
RUN ls -la /app
RUN pwd
RUN npm install
COPY . /app/
#COPY index.js ./
EXPOSE 8081
CMD [ "node", "index.js"]
