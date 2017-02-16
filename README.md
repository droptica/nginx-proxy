# nginx-proxy


## Letsencrypt

This repo has a branch 'letsencrypt' which adds a https://letsencrypt.org demon to get and periodically update ssl certs

Each host that will use letsenctrypt needs to have hosts specified.

If your website uses a subdomain (eg www.example.com) but you also point a highier level eg example.com on the same server, both need to be added. Letsencrypt checks from top to bottom.

```bash
LETSENCRYPT_HOST: example.com,www.example.com
LETSENCRYPT_EMAIL: youremail@example.com
```
