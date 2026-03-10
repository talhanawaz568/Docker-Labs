FROM node:14
WORKDIR /usr/src/app
COPY . .
RUN npm install
EXPOSE 80
CMD ["npm", "start"]
HEALTHCHECK --interval=30s --timeout=10s --retries=3 \
CMD curl -f http://localhost:80/ || exit 1
