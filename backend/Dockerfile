FROM node:18-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install --production

COPY . .

ENV MONGODB_URI="mongodb+srv://shashankkarigowda8617:AjWsrAjz4tMM2MGE@cluster0.xto60.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0"
ENV JWT_SECRET="JWT^&*_SECRET"

EXPOSE 4000

CMD ["node", "server.js"]
