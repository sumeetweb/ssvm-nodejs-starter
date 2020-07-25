build:
  docker:
    web: Dockerfile
run:
  web: bundle exec node /app/node/app.js
  worker:
    command:
      - node /app/node/app.js
    image: web
