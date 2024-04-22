FROM node:20-alpine

# USER root
# RUN addgroup app && adduser -S -G app app
# RUN chown -R app:app .
# USER app

WORKDIR /app
COPY package*.json ./
RUN npm i
COPY . .

EXPOSE 5173
CMD npm run dev