FROM node:14-alpine

WORKDIR /app

COPY . .

EXPOSE 3000

ADD ./node_modules.tar.gz .

CMD ["npm", "start"]
