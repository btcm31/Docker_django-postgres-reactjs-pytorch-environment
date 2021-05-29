FROM node

WORKDIR /app/frontend
COPY package.json /app/frontend

RUN npm install npm@7
RUN npm install

EXPOSE 3000
CMD ["npm", "start"]