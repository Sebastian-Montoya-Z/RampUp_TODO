FROM node:8.17
WORKDIR /todos
EXPOSE 8082
COPY package*.json ./
RUN npm install
COPY . .
CMD ["sh", "-c", "npm start" ]