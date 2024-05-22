FROM node:18
WORKDIR /app
ADD package*.json ./
RUN npm install
ADD index.js ./
EXPOSE 3000
CMD ["node", "index.js"]