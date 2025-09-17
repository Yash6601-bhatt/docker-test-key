FROM node:20-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install --only=production --legacy-peer-deps
COPY . .
EXPOSE 3000
CMD ["node", "index.js"]