FROM node:16
WORKDIR /app
COPY pacakge*.json /app
RUN npm install
COPY . /app
ENV PORT=3000
ENV DB_USER=postgres
ENV DB_HOST=countries-db
ENV DB_NAME=countries
ENV DB_PASSWORD=docker
ENV DB_PORT=5432
EXPOSE 3000
CMD ["node", "index.js"]