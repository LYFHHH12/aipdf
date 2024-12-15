FROM node:latest
RUN mkdir -p /www
WORKDIR /www
COPY . /www
RUN npm install
EXPOSE 5001
ENTRYPOINT ["npm", "run", "start"]
