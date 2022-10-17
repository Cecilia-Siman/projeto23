FROM node:18

WORKDIR /user/src

COPY . .

EXPOSE 5000

RUN npm i
RUN npm run build


CMD ["npm", "start"]