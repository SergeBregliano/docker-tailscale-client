# docker-tailscale-client
Basic Tailscale container managed with Docker Compose.



## Install

Rename the ``sample.env`` file to ``.env``.

Configure the ``.env`` file with the required values.

Run ``docker compose up -d`` or ``docker-compose up -d`` for older versions of Docker Compose.

To finalize the configuration, you'll need to authenticate the container to Tailscale:

### Authenticate

Run the command-line command to connect your container to Tailscale:

```shell
docker exec tailscale tailscale up
```
