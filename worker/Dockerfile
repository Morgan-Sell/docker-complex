FROM node:14.14.0-alpine
WORKDIR "/app"
COPY ./packag.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "start"]