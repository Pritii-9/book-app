FROM node:22-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install 

EXPOSE 5000

COPY . .
CMD ["npm", "start"]
# CMD ["sh", "-c", "env && sleep 1000"]
