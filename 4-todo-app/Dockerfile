FROM node
WORKDIR /opt/todo-app
COPY . .
ENV PORT=4000
EXPOSE 4000
RUN npm install
CMD ["node", "app.js"]