build:
  docker:
    web: Dockerfile
run:
  web: bundle exec node /app/node/app.js
  worker:
    command:
      - cd /app
      - ssvmup build
    image: web
