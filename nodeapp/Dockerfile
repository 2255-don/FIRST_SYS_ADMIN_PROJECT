FROM node:20
WORKDIR /home/traore/project_personnel
COPY package.json .
RUN npm install
COPY . .
EXPOSE 8081
CMD ["node", "app.js"]