# FocusControl-Server
A FocusControl Server

## Launch

Install environment :
```sh
npm i
npm i typescript --global
npx tsc
```

Launch server :
```sh
npm run start
```

Access api :
http://localhost:8080/

## Dockerize

```sh
docker build --pull -t "focus-server-$TAG" --no-cache .
```

```sh
docker run -d --name="focus-server-$TAG" -p 8080:8080/tcp "focus-server-$TAG"
```