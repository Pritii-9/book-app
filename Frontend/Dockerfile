FROM node:22-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install 

EXPOSE 5173

COPY . .
# copies windows files to linux, so we need to change the line endings
# line endings in windows are \r\n, while in linux they are \n
CMD ["npm", "run", "dev"]
