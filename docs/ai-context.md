# Djuphelg – AI-kontext

## Syfte med dokumentet

Detta dokument ska göra det möjligt för en ny AI-assistent eller projektmedlem att snabbt förstå Djuphelg utan tillgång till tidigare konversationer.

Vid fortsatt arbete ska detta dokument, tillsammans med övriga filer i `docs/`, behandlas som projektets huvudsakliga kontext.

## Projektöversikt

**Djuphelg – Gullmarn** är en deltagardriven fridykningshelg.

Pilothelgen är planerad till:

- **Datum:** 14–16 augusti 2026
- **Plats:** Fossens Camping vid Gullmarn
- **Format:** deltagardriven helg
- **Initiativtagare:** Max Franklin
- **Deltagaravgift:** ingen

Djuphelg ska inte fungera som ett traditionellt kommersiellt evenemang där en arrangör säljer ett färdigt program till kunder. Initiativtagaren tillhandahåller i stället en ram, grundläggande säkerhet och nödvändig logistik. Deltagarna skapar tillsammans innehållet.

## Grundidé

Deltagarna ska inte ses som publik eller kunder.

De kan bidra med exempelvis:

- workshops
- coachning
- safetypass
- yoga eller andningsövningar
- matlagning
- morgonkaffe
- skjuts
- utlåning av utrustning
- disk
- praktisk hjälp
- en berättelse eller erfarenhet
- att upptäcka och lösa något som behöver göras

Både synliga och osynliga bidrag ska uppmärksammas.

En viktig formulering är:

> Vi värderar inte gåvor efter hur synliga de är, utan efter att de ges.

## Inspirationskälla

Djuphelg är inspirerad av principer som deltagande, gåvokultur, medskapande och självorganisering, bland annat från Burning Man.

Djuphelg ska dock **inte beskrivas som Burning Man**, och språket ska undvika att skapa felaktiga associationer till festival, sekt, kommersialism eller överdriven spiritualitet.

## Ekonomi

Ingen deltagaravgift tas ut.

Varje deltagare betalar själv för:

- resa
- camping
- egen mat, om den inte delas eller ges av någon annan

Målet är att minimera ekonomiska transaktioner mellan deltagarna.

Kunskap, aktiviteter, hjälp och måltider ges i första hand som gåvor.

Framtida gemensamma kostnader för faktisk infrastruktur kan förekomma, exempelvis båtar, syrgas, säkerhetsutrustning, webbplats eller gemensamma transporter. Sådana kostnader ska hållas separata från gåvokulturen och hanteras transparent.

## Initiativ och organisering

I stället för en central programlista eller en traditionell önskelista ska deltagarna kunna föreslå initiativ.

Varje initiativ kan skapa egna behov, exempelvis utrustning, medhjälpare, tid, transport, plats eller råvaror.

Initiativtagaren samordnar centralt endast sådant som är nödvändigt för säkerhet och grundläggande dyklogistik.

## Det gemensamma dyket

En återkommande tradition är planerad under namnet **Det gemensamma dyket**.

Det är en guidad visualiseringsövning där gruppen tillsammans föreställer sig ett djupt fridyk genom Gullmarn.

Syften:

- ge alla möjlighet att mentalt uppleva ett djupt dyk
- fungera som legitim visualiseringsträning
- skapa en gemensam upplevelse
- öppna för ett inre djup utan att göra övningen uttalat spirituell

Föreslagen formulering:

> Vi följer linan ner genom Gullmarn, men kanske också en bit djupare in i oss själva.

Första året leder Max övningen.

Framtida år kan en erfaren deltagare leda den som en gåva till gruppen. Förmågan att guida en upplevelse är viktigare än personens maximala dykdjup.

Ordet **ceremoni** ska undvikas.

## Kultur kring uppskattning

Djuphelg ska aktivt motverka att endast stora och synliga bidrag får uppskattning.

Möjliga former:

- kort tacksamhetsrunda på kvällen
- deltagare tackar andra för konkreta handlingar
- synliggöra sådant som skjuts, disk, inköp, säkerhet och omsorg
- undvika rangordning av bidrag

## Webbplats

Webbplatsen är redan publicerad via GitHub Pages.

- Repository: `https://github.com/maxfrankli/djuphelg`
- Tidigare GitHub Pages-adress: `https://maxfrankli.github.io/djuphelg/`
- Egen domän: `djuphelg.se`
- Registrar: Loopia
- DNS: Cloudflare
- Hosting: GitHub Pages
- Teknik: statisk HTML och CSS

Webbplatsen ska vara mobilanpassad, snabb, enkel att underhålla, fri från onödiga ramverk, lugn, naturnära och icke-kommersiell i uttrycket.

Estetisk riktning:

- mörkt blågrönt
- mycket luft
- Gullmarn och natur
- hög kvalitet utan lyxmarknadsföring
- undvik neonblå sportestetik
- undvik aggressiva call-to-action-knappar
- känslan kan beskrivas som “Patagonia möter Apple”, utan att imitera något varumärke

## Aktuell teknisk status

Följande är genomfört:

- GitHub-repository skapat
- första versionen av webbplatsen uppladdad
- GitHub Pages aktiverat från `main` och repositoryts rot
- `djuphelg.se` angivet som Custom domain i GitHub Pages
- domänen registrerad hos Loopia
- Cloudflare Free har lagts till
- namnservrar hos Loopia har ändrats till:
  - `ashton.ns.cloudflare.com`
  - `rosemary.ns.cloudflare.com`
- GitHub Pages DNS-poster finns i Cloudflare
- samtliga GitHub-poster är satta till **DNS only**

DNS-poster:

| Typ | Namn | Innehåll |
|---|---|---|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `maxfrankli.github.io` |

Vid senaste uppdateringen väntade Cloudflare på att namnserverbytet skulle propagera. Aktuell status bör verifieras innan ändringar görs.

## E-post

Planerad lösning:

- adress: `info@djuphelg.se`
- Cloudflare Email Routing
- vidarebefordran till Max privata Gmail

E-postlösningen är ännu inte bekräftad som färdig.

## Ton och språk

Språket ska vara lugnt, direkt, inkluderande, konkret, eftertänksamt och icke-säljande.

Undvik överdrivna superlativ, sektliknande eller ritualiserat språk, kommersiell eventjargong, löften om upplevelser och att beskriva deltagare som kunder.

## Beslutsprincip för framtida förslag

När ny funktionalitet eller nya aktiviteter föreslås ska frågan ställas:

> Stärker detta deltagande, enkelhet, säkerhet och medskapande – eller gör det helgen mer kommersiell, toppstyrd eller administrativ?

Välj i regel den enklaste lösningen som stödjer filosofin.
