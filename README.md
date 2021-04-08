# redpanda-evaluation

## Quickstart

Ensure that the config files have the group id `101` to match the process running within the docker container. This is required as the `rpk` process will write back to the config file.

```shell
$ sudo chgrp 101 redpanda/*.yaml
```

The start all services with `docker-compose up -d`. 

