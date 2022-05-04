# LocalSecret
An instant, zero-config Secret Network blockchain.

```bash
docker run -it -p 9091:9091 -p 26657:26657 -p 1317:1317 -p 5000:5000 --name localsecret ghcr.io/scrtlabs/localsecret
```

Full docs: https://docs.scrt.network/dev/LocalSecret.html

# Source

You can trace everything from `build-localsecret` in [`Makefile`](https://github.com/scrtlabs/SecretNetwork/blob/master/Makefile), but the gist of it is in [`bootstrap_init_no_stop.sh`](https://github.com/scrtlabs/SecretNetwork/blob/master/deployment/docker/devimage/bootstrap_init_no_stop.sh).
