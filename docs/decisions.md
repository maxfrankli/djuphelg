# Beslutslogg

Senast uppdaterad: 2026-07-24

Den här filen innehåller beslut som ska behandlas som kända vägval tills Max ändrar dem.

## Evenemang

- Namnet är **Djuphelg - Gullmarn**.
- Första provomgången hålls 14-16 augusti 2026.
- Basen är Fossens Camping vid Gullmarn.
- Initiativtagaren är värd och ramskapare, inte traditionell totalarrangör.
- Deltagarna skapar innehållet tillsammans.
- Första året beskrivs publikt som en första provomgång i mindre omfattning, inte som huvuddefinitionen av Djuphelg.
- Lördag och söndag finns två planerade ramar för djupdykning per dag.
- Även dyktillfällena bygger på deltagarnas medverkan och ansvar.
- Ingen deltagaravgift tas ut.
- Deltagarna betalar själva resa, boende och mat.
- Helgen utgår från Fossens Camping och tanken är att de flesta bor där.
- Deltagare kan lösa boende på annat sätt.
- Minimikrav för 2026 är genomförd fridykningskurs i djup, till exempel CMAS One Star Apnea eller motsvarande.
- Alla som uppfyller kravet får anmäla sig.
- Om fler anmäler sig än det finns plats för gäller först till kvarn.
- Preliminärt maxantal är ungefär 20 personer, men det behöver inte nödvändigtvis skrivas ut publikt.

## Kultur och innehåll

- Djuphelg ska inte vara ett färdigpaketerat event med passiva deltagare.
- Kunskap, aktiviteter, måltider och hjälp ges i första hand som gåvor.
- Bidrag kan vara stora, små, synliga eller osynliga.
- Synliga och osynliga bidrag ska uppmärksammas.
- Exempel på innehåll: workshops, coachning, erfarenhetsutbyte, samtal, gemensamma måltider, transport, utrustningshjälp och praktiska initiativ.
- En initiativtavla kan bli relevant senare, men ska inte bli ett avancerat bokningssystem.
- Kvällstacksamhet kan prövas i enkel och frivillig form.

## Säkerhet

- Säkerhet och nödvändig dyklogistik samordnas centralt.
- Dykpar matchas efter nivå.
- Dykpar fungerar som buddy och säkerhetsdykare för varandra.
- Mer oerfarna dykare får stöd av säkerhetsdykare och/eller coacher under passen.
- En full säkerhetsplan behöver tas fram separat före helgen.

## Anmälan

- Anmälan sker via Google Forms: `https://forms.gle/61C4yt1fkdc4LoJy9`.
- Formuläret är en riktig anmälan för personer som planerar att komma, inte en lös intresseanmälan.
- Knappen på hemsidan heter **Anmäl dig**.
- `info@djuphelg.se` visas på sidan för frågor.

## Webbplats

- Webbplatsen byggs som statisk HTML och CSS.
- GitHub Pages används för hosting.
- Repositoryt är publikt.
- Inga lösenord, deltagaruppgifter, medicinska uppgifter eller hemligheter får läggas i repot.
- Webbplatsen ska vara mobilanpassad och enkel att underhålla.
- Uttrycket ska vara lugnt, naturnära och icke-kommersiellt.
- Starka säljtekniker och aggressiva call-to-actions ska undvikas.
- Publika startsidan ska vara kort: hero, kort vision, praktisk förklaring och tydlig anmälan.
- Publika sidan ska inte nämna **Det gemensamma dyket** i nuläget.
- Anmälan sker via Google Forms: `https://forms.gle/61C4yt1fkdc4LoJy9`.
- Formuläret är en riktig anmälan för personer som planerar att komma, inte en lös intresseanmälan.
- `info@djuphelg.se` visas på sidan för frågor.
- Externa länkar på sidan öppnas i ny flik.
- Open Graph/Twitter-metadata finns i `index.html`.
- Social delningsbild är `assets/og-image.jpg` i formatet 1200x630.
- Domänen är `djuphelg.se`.

## Det gemensamma dyket

- Den gemensamma visualiseringen heter **Det gemensamma dyket**.
- Ordet **ceremoni** ska undvikas.
- Övningen ska vara legitim visualiseringsträning.
- Den får ha ett subtilt inre djup men ska inte marknadsföras som spirituell.
- Max leder den första året.
- Framtida ledare väljs utifrån förmåga att guida upplevelsen, inte endast maximalt personbästa.

## Infrastruktur

- Domänen är registrerad hos Loopia.
- Loopias betalda DNS-tjänst används inte.
- Cloudflare Free används för DNS.
- GitHub Pages-posterna ligger som DNS only.
- `djuphelg.se` fungerar med GitHub Pages och HTTPS är aktiverat.
- `www.djuphelg.se` fungerar.
- `CNAME` finns i repositoryts rot och innehåller `djuphelg.se`.
- Cloudflare Email Routing används för `info@djuphelg.se`.
- Svar från e-post kan skickas så mottagaren ser `info@djuphelg.se` som avsändare.
