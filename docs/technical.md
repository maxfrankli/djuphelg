# Teknisk dokumentation

## Översikt

- **Repository:** `https://github.com/maxfrankli/djuphelg`
- **Hosting:** GitHub Pages
- **Domän:** `djuphelg.se`
- **Registrar:** Loopia
- **DNS-leverantör:** Cloudflare
- **Cloudflare-plan:** Free
- **Teknik:** HTML och CSS
- **Publiceringsgren:** `main`
- **Publiceringsmapp:** repositoryts rot, `/`

## GitHub Pages

GitHub Pages är konfigurerat att publicera webbplatsen direkt från `main`.

GitHub Pages-adress före egen domän:

`https://maxfrankli.github.io/djuphelg/`

Custom domain i GitHub:

`djuphelg.se`

## Namnservrar

Loopia har uppdaterats till Cloudflares namnservrar:

- `ashton.ns.cloudflare.com`
- `rosemary.ns.cloudflare.com`

Vid senaste dokumenterade status väntade Cloudflare fortfarande på full namnserverpropagation.

## DNS-poster i Cloudflare

| Typ | Namn | Innehåll | Proxy |
|---|---|---|---|
| A | `@` | `185.199.108.153` | DNS only |
| A | `@` | `185.199.109.153` | DNS only |
| A | `@` | `185.199.110.153` | DNS only |
| A | `@` | `185.199.111.153` | DNS only |
| CNAME | `www` | `maxfrankli.github.io` | DNS only |

Gamla parkeringsposter mot Loopias IP-adresser `194.9.94.85` och `194.9.94.86` har tagits bort.

## HTTPS

När namnservrar och DNS har propagerat ska följande kontrolleras:

1. GitHub verifierar `djuphelg.se`.
2. `Enforce HTTPS` blir tillgängligt i GitHub Pages.
3. HTTPS aktiveras.
4. `https://djuphelg.se` och `https://www.djuphelg.se` testas.

## Cloudflare-proxy

GitHub-posterna är initialt satta till **DNS only**. Cloudflare-proxy ska inte aktiveras utan ett tydligt skäl och test.

## E-post

Planerad lösning:

- Cloudflare Email Routing
- `info@djuphelg.se`
- vidarebefordran till Max Gmail

Att skicka som `info@djuphelg.se` från Gmail kan kräva ytterligare SMTP-lösning och är inte samma sak som gratis vidarebefordran.

## Ändringsprincip

Lägg aldrig lösenord, API-nycklar, deltagarlistor, privata mejladresser, medicinska uppgifter eller andra hemligheter i det publika repot.
