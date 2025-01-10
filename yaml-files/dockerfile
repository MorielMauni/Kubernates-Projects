# Example
FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD [ "node", "app.mjs" ]

# 'docker build .'
# 'docker run -p <port> <id>'
# 'docker ps'
# 'docker stop <name>'
