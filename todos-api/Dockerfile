FROM node:8.17
WORKDIR /todos
EXPOSE 8082
COPY package*.json ./
COPY . .
RUN ls -la
RUN npm install
CMD JWT_SECRET=PRFT TODO_API_PORT=8082 npm start