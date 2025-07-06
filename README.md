# dockerized-plex

## Setup

1. Set your open vpn file in `gluetun/openvpn/yourfile.ovpn`  
2. In .env set your credentials, you have to choose the right VPN (Proton VPN in my case) credentials according to your open vpn file.

> Your VPN credentials are not the same as your Open VPN file, see OpenVPN / IKEv2 username/password


## Start

```sh
docker-compose up -d
```

## Access

### Qbittorrent
http://localhost:8080

> The credentials are in the log of the container, you can change it in Tools > Options > Web UI > Authentication

### Plex
http://localhost:32400/web
