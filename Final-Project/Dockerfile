FROM node


WORKDIR /usr/src/node-getting-started	

COPY package*.json ./
RUN npm install

COPY . .  

EXPOSE 8080

CMD [ "node", "./bin/www" ]
