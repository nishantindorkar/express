FROM node:18.19.1-alpine
WORKDIR /app
COPY package*.json /var/lib/jenkins/workspace/examples/hello-world/
RUN npm install
COPY index.js ./
CMD [ "node", "index.js"]