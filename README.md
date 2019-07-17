# Cloudflare DNS Updater

Shell script that will dynamically update a [Cloudflare](https://www.cloudflare.com/) DNS record to the server's public IP (using the https://checkip.amazonaws.com/ API) every 5 minutes, using a systemd timer.

## Installation (root or installed sudo required)
```
git clone https://github.com/moqmar/cf-dns-update.git /tmp/cf-dns-update && cd /tmp/cf-dns-update
source install
```
