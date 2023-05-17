FROM node:14-alpine
WORKDIR /app
COPY . /app
RUN yarn install
ENV NODE_ENV=production
EXPOSE 4000
CMD ["yarn", "start"]
