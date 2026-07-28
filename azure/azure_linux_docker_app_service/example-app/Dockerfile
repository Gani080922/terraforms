FROM node:26.5.0-alpine3.24

WORKDIR /app
COPY package.json package-lock.json ./
RUN npm ci
COPY index.js ./

EXPOSE 4000
CMD ["node", "index.js"]
