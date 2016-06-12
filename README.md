# kwiiu

## What is kwiiu?

kwiiu is a HaxServer alternative written on PHP

## How to use this image

### Binaries list

- cafiine
- elfloader
- kexploit31
- loadiine
- sdcafiine
- dumpiine
- kexploit10
- launcher
- rpccode
- tcpgecko

### Start a kwiiu server instance

```
docker run --name kwiiu -p 80:80 -d vbtyler042/kwiiu:latest
```

### On your WiiU

http://\<DOCKER_SERVER_IP\>/kwiiu.php?bin=\<BINARIE_NAME\>

### Example

http://192.168.0.2/kwiiu.php?bin=kexploit10
