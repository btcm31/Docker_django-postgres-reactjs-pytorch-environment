FROM node

WORKDIR /app/frontend
COPY package.json /app/frontend

RUN npm install -g npm@7.15.0
RUN npm install

EXPOSE 3000
CMD ["npm", "start"]