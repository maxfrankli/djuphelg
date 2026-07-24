# Djuphelg - AI-kontext

Senast uppdaterad: 2026-07-24

Det här är första filen en ny AI-agent bör läsa. Den sammanfattar projektet, nuläget och de viktigaste besluten.

## Projektet

**Djuphelg - Gullmarn** är en deltagardriven fridykningshelg vid Gullmarn.

Första provomgången:

- **Datum:** 14-16 augusti 2026
- **Bas:** Fossens Camping vid Gullmarn
- **Initiativtagare:** Max Franklin
- **Deltagaravgift:** ingen
- **Anmälan:** Google Forms, `https://forms.gle/61C4yt1fkdc4LoJy9`
- **Kontakt:** `info@djuphelg.se`

Djuphelg ska inte kännas som ett kommersiellt event där arrangören säljer ett färdigt program. Initiativtagaren skapar ramen, grundläggande säkerhet och nödvändig dyklogistik. Deltagarna skapar resten tillsammans.

## Publik positionering

Hemsidan ska börja med Djuphelg som koncept, inte med att kalla allt för pilothelg. Årets mindre format förklaras längre ner som **en första provomgång**.

Sidan ska vara kort och koncis:

1. Hero
2. Kort vision
3. Praktisk förklaring
4. Kort information och anmälan

Den publika sidan ska skapa intresse och få rätt personer att anmäla sig. Mer detaljerad information, samordning och Slack kan komma senare till anmälda deltagare.

## Ton

Skriv på svenska. Tonen ska vara lugn, konkret, mänsklig och icke-säljig.

Undvik:

- aggressiva call-to-actions
- kommersiell eventjargong
- överdrivna superlativ
- sektliknande eller ritualiserat språk
- att beskriva deltagare som kunder
- att kalla Djuphelg för Burning Man

Det är okej att vara varm och inbjudande, men sidan ska främst vara en tydlig infosida för ett deltagardrivet arrangemang.

## Grundfilosofi

Deltagarna är inte publik. Alla kan bidra med något, stort eller litet.

Exempel på bidrag:

- workshops
- coachning
- erfarenhetsutbyte
- samtal
- fika eller mat
- transport
- gemensam utrustning
- foto
- praktisk hjälp
- disk, städning eller sådant som bara behöver göras

Nuvarande formulering på hemsidan:

> Tanken är enkel: ser du något som skulle göra helgen bättre, större eller lättare för någon annan, så är det värt att göra.

Intern filosofisk formulering som fortfarande gäller:

> Vi värderar inte gåvor efter hur synliga de är, utan efter att de ges.

Den senare är bra som intern princip, men kan kännas för principtung på den publika sidan.

## 2026 års upplägg

Lördag och söndag finns två planerade ramar för djupdykning per dag. De ska inte beskrivas som ett färdigserverat program. Även dyktillfällena bygger på att deltagarna dyker, hjälper till och tar ansvar tillsammans.

Allt annat innehåll skapas av deltagarna.

Boende:

- Helgen utgår från Fossens Camping.
- Tanken är att de flesta bor där.
- Det är okej att lösa boende på annat sätt, till exempel om man bor i närheten.

Kostnad:

- Ingen deltagaravgift.
- Deltagare betalar själva resa, boende och mat.

## Deltagarkrav

För 2026 krävs genomförd fridykningskurs i djup, till exempel CMAS One Star Apnea eller motsvarande.

Formulering på hemsidan:

> Djupkurs i fridykning, till exempel CMAS One Star Apnea.

Alla som uppfyller kravet får anmäla sig. Om fler anmäler sig än det finns plats för gäller först till kvarn.

Preliminär övre riktning är ungefär max 20 deltagare, men det behöver inte nödvändigtvis stå på hemsidan.

## Säkerhet

Säkerhet ska vara tydligt prioriterad, men detaljer ska inte låsas på hemsidan innan säkerhetsplanen är färdig.

Publik nivå just nu:

- Dykpar matchas efter nivå.
- Dykpar fungerar som buddy och säkerhetsdykare för varandra.
- Mer oerfarna dykare får stöd av säkerhetsdykare och/eller coacher under passen.

Säkerhetsplanen behöver fortfarande utvecklas separat.

## Anmälan

Anmälan sker via Google Forms:

`https://forms.gle/61C4yt1fkdc4LoJy9`

Det ska beskrivas som en riktig anmälan för personer som planerar att komma, inte som en lös intresseanmälan.

Hemsidans knapp bör heta:

> Anmäl dig

`info@djuphelg.se` används för frågor.

## Det gemensamma dyket

Det finns en planerad tradition med arbetsnamnet **Det gemensamma dyket**, en guidad visualisering kopplad till fridykning.

Viktigt:

- Ska inte nämnas på publika hemsidan i nuläget.
- Ordet **ceremoni** ska undvikas.
- Får ha subtilt inre djup, men ska inte marknadsföras som spirituellt.
- Max leder första året.

## Teknisk status

Webbplats:

- Statisk HTML och CSS.
- Hosting via GitHub Pages.
- Publiceras från `main` och repositoryts rot.
- Domän: `djuphelg.se`.
- `https://djuphelg.se` fungerar.
- `https://www.djuphelg.se` fungerar.
- Enforce HTTPS är aktiverat.
- `CNAME` finns i roten och innehåller `djuphelg.se`.

DNS:

- Registrar: Loopia.
- DNS: Cloudflare Free.
- GitHub Pages-poster ligger som DNS only.

E-post:

- `info@djuphelg.se` fungerar.
- Cloudflare Email Routing används.
- Svar är konfigurerat så mottagaren ser `info@djuphelg.se` som avsändare.

## Kvarvarande fokus

Högst värde härnäst:

- Testa Facebook-preview igen efter publicering.
- Lägg till favicon.
- Säkerställ bildrättigheter.
- Ta fram riktig säkerhetsplan.

## Arbetsprincip

När du föreslår nya saker, kontrollera först:

1. Är det redan beslutat i `docs/decisions.md`?
2. Stärker det deltagande, enkelhet, säkerhet och medskapande?
3. Gör det sidan tydligare utan att göra den längre än nödvändigt?
4. Bygger det på fakta, eller kräver det beslut från Max?

Ändra inte säkerhetskritiska detaljer utifrån antaganden.
