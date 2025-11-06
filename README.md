redis-action
============

### DevTunnel
- See [dirkarnez/devtunnel-playground](https://github.com/dirkarnez/devtunnel-playground)

### `redis-cli` (`docker run -d --name redis -p 6378:6379 redis:latest` local docker use another port to avoid clash)
- [Run Redis Open Source on Docker | Docs](https://redis.io/docs/latest/operate/oss_and_stack/install/install-stack/docker/)
  - `docker exec -it redis redis-cli -h 127.0.0.1 -p 6379`

### Web UI
- `https://${Tunnel ID}.devtunnels.ms:6379/`

### Notes
- `sudo chmod -R +x . && ./build.sh` in CI/CD .yaml file is good enough for running docker build on GitHub Action
- too busy - use Docker image instead
