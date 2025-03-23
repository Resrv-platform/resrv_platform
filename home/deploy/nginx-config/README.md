# NGINX-configuratie voor client.rms.resrv.nl

Deze repo bevat de volledige setup voor:

- Reverse proxy + iframe hosting via NGINX
- Clientsubdomein (`client.rms.resrv.nl`) dat de Bubble-app laadt
- Let’s Encrypt configuratie

## Structuur

- `domains/` → losse NGINX-configs per domein/subdomein
- `www/` → statische HTML-bestanden zoals index.html voor iframe-hosting
- `includes/` → herbruikbare NGINX blocks (bijv. headers)
- `certbot/` → map voor tijdelijke Let’s Encrypt challenges
