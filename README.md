# Software as a Container (SaaC)

These are the list of softwares that I install every time I install a new version of Ubuntu.

I never liked doing repeated work.

Now, I can run a single command to run these softwares as a container. Also, updating their version is as easy as changing the version number in a relevant `compose.yml` file. Thanks to Docker!

## To run the services
```shell
$ docker compose -f compose.main.yml up
```

## To stop the services
```shell
$ docker compose -f compose.main.yml stop
```

or stop and remove the containers and network

```shell
$ docker compose -f compose.main.yml down
```

or stop and remove the containers, images and network automatically

```shell
$ docker compose -f compose.main.yml down --rmi all
```
