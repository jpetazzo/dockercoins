FROM node:22-slim
WORKDIR /app
RUN npm install express
RUN npm install redis@3
COPY . .
CMD ["node", "webui.js"]
EXPOSE 80
