FROM node:alpine
WORKDIR /app
COPY guest-book-in-memory .
EXPOSE 3000
RUN npm install
CMD ["node", "app.js"]