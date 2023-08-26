FROM node:18-alpine

WORKDIR /app

COPY package* ./

RUN npm i

# Copy the rest of the application code to the container
COPY . ./

EXPOSE 8000

CMD ["npm", "run", "develop"]
