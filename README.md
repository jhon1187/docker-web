## INSTALL
Run `npm install`

## RUN
Run `npm start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## BUILD
Run `npm run build:<env>` to build the project. The build artifacts will be stored in the `dist/` directory.

## DOCKER BUILD
Run `docker build -t docker-web -f Dockerfile-<env> .`

## DOCKER RUN
Run `docker run -d --name docker-web -p 3000:80 docker-web` . Navigate to `http://localhost:3000/docker-web`
