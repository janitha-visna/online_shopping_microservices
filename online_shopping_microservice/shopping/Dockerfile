from node

WORKDIR /app/shopping

COPY package.json .

RUN npm install

COPY . .

EXPOSE 8004

CMD [ "npm" , "start" ]