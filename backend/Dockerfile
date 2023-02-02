FROM node:16-alpine
WORKDIR /app
COPY . .
RUN cp .env.example .env
RUN npm install 
EXPOSE 5000
CMD ["npm","start"]