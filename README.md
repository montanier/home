# home
Configuration for home's website

To start website:

Set in `.bashrc` the following variables:
- `OAUTH2_PROXY_CLIENT_SECRET`
- `OAUTH2_PROXY_CLIENT_ID`
- `OAUTH2_PROXY_COOKIE_SECRET`

Run `certbot` to get the following files configured locally:
- `/etc/letsencrypt/live/amuel.duckdns.org/fullchain.pem`
- `/etc/letsencrypt/live/amuel.duckdns.org/privkey.pem`

Finally, run the following command:
```bash
cd config
docker-compose up --detach
```
