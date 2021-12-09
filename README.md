# TON Proxy
This docker image allows you to setup a proxy to the TON network

# Usage

To start a simple proxy:

```bash
docker run -p 8080:8080 -p 3333:3333 -d tonwhales/ton-proxy -p 8080 -c 3333 -C /usr/local/bin/global.config.json
```

# Building image

```bash
docker build --platform linux/amd64 -t tonwhales/ton-proxy:v1 -t tonwhales/ton-proxy:latest .
```

# License

MIT