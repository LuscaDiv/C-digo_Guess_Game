FROM node:20

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

# Comando padrão para iniciar o app
CMD ["yarn", "start"]
