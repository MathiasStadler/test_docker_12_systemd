# I'm explore this short tutorial see. [FROM_HERE](./FROM_HERE.md)

> [!IMPORTANT]
> I'm use my raspberry pi4/8GB /w GNU/Linux 11 (bullseye)

## pull docker images

```bash
docker pull trfore/docker-debian12-systemd
```

## run container

```bash
docker run -d -it --name debian12-systemd --privileged --cgroupns=host --tmpfs=/run --tmpfs=/tmp --volume=/sys/fs/cgroup:/sys/fs/cgroup:ro trfore/docker-debian12-systemd:latest
```

## [get docker file from github.com] (https://github.com/trfore/docker-debian12-systemd)
