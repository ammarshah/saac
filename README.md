# Software as a Container (SaaC)

These are the list of softwares that I install every time I install a new version of Ubuntu.

I never liked doing repeated work.

Now I can run a single command to run these softwares as a container. Thanks to Docker!

## To run the services
```shell
$ docker compose up

# or run a specific service
$ docker compose up stremio
```

## To stop the services
```shell
$ docker compose stop
```

or stop and remove the containers and network

```shell
$ docker compose down
```

or stop and remove the containers, images and network automatically

```shell
$ docker compose down --rmi all
```
