# STAPI

The project is generated by [LoopBack](http://loopback.io).

## Gettin started

Current datasource is connected to a mongo atlas cluster. You need to set up the `MONGODB_URL` environment variable.

## Run the server locally

Run the following command:

```
MONGODB_URL=<mongo-connection-string> npm run dev
```

## Deploy with now.sh

Run the following commands:

```
now secrets add mongodb-url <mongo-connection-string>
now -e MONGODB_URL=@mongodb-url
```

