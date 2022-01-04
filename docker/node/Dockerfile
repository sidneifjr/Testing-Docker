FROM node:16.13

WORKDIR /frontend

COPY ./frontend /frontend

RUN npm install

EXPOSE 9000

CMD ["yarn", "run", "dev"]
