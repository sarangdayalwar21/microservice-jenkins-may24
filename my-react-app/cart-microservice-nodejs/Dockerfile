FROM node
WORKDIR /app
COPY package*.json ./
RUN npm install
EXPOSE 1004
CMD [ "node", "index.js" ]
COPY . .
