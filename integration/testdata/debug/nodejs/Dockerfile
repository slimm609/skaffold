FROM node:10.15.3-alpine

WORKDIR /opt/backend
EXPOSE 3000
CMD ["node", "src/index.js"]

COPY . .
RUN npm ci
