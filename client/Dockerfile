FROM node:14.21.0-alpine

WORKDIR '/app'

COPY package.json .
COPY package-lock.json .
RUN npm install --loglevel=error

COPY . .

CMD ["npm", "run", "start"]
