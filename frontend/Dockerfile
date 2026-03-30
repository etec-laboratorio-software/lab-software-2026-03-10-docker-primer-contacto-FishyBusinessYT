FROM node:22-slim
WORKDIR /app
COPY package.json package-lock.json ./
RUN npm install

COPY . .
EXPOSE 5173
# --host makes Vite listen on 0.0.0.0 instead of localhost,
# which is required for Docker port forwarding to work
CMD ["npm", "run", "dev", "--", "--host"]
