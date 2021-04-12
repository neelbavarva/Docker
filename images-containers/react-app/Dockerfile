FROM node:14.16.1-alpine3.13
RUN addgroup app && adduser -S -G app app
USER root
WORKDIR /app
COPY . ./
RUN npm install
EXPOSE 3000
CMD ["npm", "start"]