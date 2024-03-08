# dev instructions

run /certificates/generate_selfsigned_certs.sh. When asked for domain name, enter IP address. For all other qusetions enter '.'

In config.js 
REACT_APP_API_ENDPOINT:'https://SERVER_IP'

docker compose --profile all --env-file .env up -d