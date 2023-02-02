FROM node:16-alpine
WORKDIR /app
COPY . .
RUN cp .env.example .env
RUN npm install 
EXPOSE 3000
CMD ["npm","start"]