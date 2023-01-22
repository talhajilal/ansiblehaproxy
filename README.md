# HA Proxy 
Example taken from here "https://serversforhackers.com/c/using-ssl-certificates-with-haproxy"

# Cert Bot
https://serversforhackers.com/c/letsencrypt-with-haproxy

certbot certonly --standalone -d amjta.ca \
    --non-interactive --agree-tos --email admin@amta.ca \
    --http-01-port=80
# ansiblehaproxy
