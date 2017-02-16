# nginx-proxy

Each host that will use letsenctrypt needs to have hosts specified.

If your website uses a subdomain (eg www.example.com) but you also point a highier level eg example.com on the same server, both need to be added. Letsencrypt checks from top to bottom.

LETSENCRYPT_HOST: {{HOST}},www.{{HOST}}
LETSENCRYPT_EMAIL: admin@droptica.com
