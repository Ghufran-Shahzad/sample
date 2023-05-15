FROM node:14-alpine
WORKDIR /app
COPY entrypoint.sh /app/entrypoint.sh
COPY . /app
RUN yarn install
ENV NODE_ENV=production
EXPOSE 4000
RUN chmod +x /app/entrypoint.sh
ENTRYPOINT ["/app/entrypoint.sh"]
