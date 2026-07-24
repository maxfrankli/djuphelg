# Teknisk dokumentation

Senast uppdaterad: 2026-07-24

## Översikt

- **Repository:** `https://github.com/maxfrankli/djuphelg`
- **Hosting:** GitHub Pages
- **Domän:** `djuphelg.se`
- **Registrar:** Loopia
- **DNS-leverantör:** Cloudflare
- **Cloudflare-plan:** Free
- **Teknik:** statisk HTML och CSS
- **Publiceringsgren:** `main`
- **Publiceringsmapp:** repositoryts rot, `/`

## Aktuell status

Verifierat:

- `https://djuphelg.se` fungerar.
- `https://www.djuphelg.se` fungerar.
- GitHub Pages är konfigurerat för `djuphelg.se`.
- **Enforce HTTPS** är aktiverat.
- Webbplatsen har testats i mobil och desktop.
- `CNAME` finns i repositoryts rot.
- `CNAME` innehåller exakt `djuphelg.se`.
- Google Formuläret har testats.
- `info@djuphelg.se` fungerar.
- Svar kan skickas så mottagaren ser `info@djuphelg.se` som avsändare.
- Open Graph/Twitter-metadata finns i `index.html`.
- Social delningsbild finns i `assets/og-image.jpg` och är 1200x630.

## GitHub Pages

GitHub Pages publicerar webbplatsen direkt från:

- Branch: `main`
- Folder: `/`

Custom domain:

`djuphelg.se`

GitHub Pages-adress före egen domän:

`https://maxfrankli.github.io/djuphelg/`

## DNS

Loopia har uppdaterats till Cloudflares namnservrar:

- `ashton.ns.cloudflare.com`
- `rosemary.ns.cloudflare.com`

Cloudflare-zonen är aktiv.

DNS-poster i Cloudflare:

| Typ | Namn | Innehåll | Proxy |
|---|---|---|---|
| A | `@` | `185.199.108.153` | DNS only |
| A | `@` | `185.199.109.153` | DNS only |
| A | `@` | `185.199.110.153` | DNS only |
| A | `@` | `185.199.111.153` | DNS only |
| CNAME | `www` | `maxfrankli.github.io` | DNS only |

Cloudflare-proxy ska inte aktiveras utan tydligt skäl och test.

## HTTPS

HTTPS är aktiverat via GitHub Pages.

Verifierat:

- `https://djuphelg.se`
- `https://www.djuphelg.se`

## E-post

Aktuell lösning:

- Cloudflare Email Routing
- `info@djuphelg.se`
- vidarebefordran till Max Gmail
- mottagning testad
- svar som `info@djuphelg.se` konfigurerat

## Anmälan

Anmälan sker via Google Forms:

`https://forms.gle/61C4yt1fkdc4LoJy9`

Formuläret har testats.

## Kvar att göra tekniskt

Högst prioriterat:

- Testa Facebook-preview igen efter publicering.
- Lägg till favicon.

Övrigt:

- Kontrollera bildrättigheter.
- Eventuellt lägga till mer metadata för sökmotorer och delning.

## Säkerhet i repositoryt

Lägg aldrig detta i det publika repot:

- lösenord
- API-nycklar
- deltagarlistor
- privata mejladresser
- medicinska uppgifter
- formulärsvar
- andra hemligheter
