FROM node:22-alpine

# RUN addgroup app && adduser -S -G app app
# USER app

WORKDIR /app
COPY package*.json ./

# USER root
# RUN chown -R app:app .
# USER app

RUN npm install
COPY . .
EXPOSE 8000
# command to run the app
CMD ["npm","start"]
