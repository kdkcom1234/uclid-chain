# Run in Devlopment Mode

## Install Go

```shell
wget go1.22.3.linux-amd64.tar.gz
tar -C /usr/local -xzf go1.22.3.linux-amd64.tar.gz
```

```shell
vi .profile
```

```
PATH=$PATH:/usr/local/go/bin
PATH=$PATH:$HOME/go/bin
```

## Install Ignite

```shell
curl https://get.ignite.com/cli! | bash
```

## Serve Development Mode

```shell
ignite chain serve -v
```

## Host Status

```shell
https://호스트명:26657/status
```
