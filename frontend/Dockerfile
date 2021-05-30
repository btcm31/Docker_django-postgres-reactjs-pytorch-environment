FROM node

WORKDIR /app/frontend
COPY package.json /app/frontend
COPY package-lock.json /app/frontend

RUN npm install --silent
RUN npm install react-scripts@4.0.3 -g --silent

COPY . ./
EXPOSE 3000
CMD ["npm", "start"]