# Dig command dockerized #
This is a docker build with the linux dig command. The image is based on the Ubuntu image included the dnsutils package.

## Build
```
$ docker build -t freelyit/dig .
```

## Run
```
$ docker run --rm freelyit/dig yourdomain.com
```