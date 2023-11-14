# docker-tailscale-client
Basic Tailscale container managed with Docker Compose.



## Install

Rename the ``sample.env`` file to ``.env``.

Configure the ``.env`` file with the needed values.

Run ``docker compose up -d`` or ``docker-compose up -d`` for the oldiest versions of Docker.



To finalize the configuration, you'll need to authenticate the container to Tailscale :

Run the commande to connect your container to Tailscale :

```shell
docker exec tailscale tailscale up
```

