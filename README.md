# Poskusni izpit VS

Spletna aplikacija za pripravo na izpit za trženje enot vzajemnih skladov (ATVP).

**Stran:** https://blazerculj-max.github.io/poskusni-izpit-vs/

## Kaj ponuja

- **Poskusni izpit:** 40 vprašanj po razporeditvi pravega izpita (8/8/8/4/4/4/4) in 60 minut časa. Najprej se izberejo vprašanja, ki jih še nisi videl. Na koncu dobiš rezultat po sklopih in pregled odgovorov z razlagami.
- **Vadba po sklopih:** brez časovne omejitve. Po vsakem odgovoru takoj vidiš rešitev in pojasnilo.
- **Zgrešena vprašanja:** napačno odgovorjena vprašanja se shranijo za ponovitev.

Banka obsega 356 vprašanj iz gradiv vseh sedmih sklopov, preverjenih ob originalnih gradivih. Večina jih ima najprej oštevilčene trditve, nato kombinirane odgovore (npr. »1, 2 in 4«, »vse razen 3«). Vmes so klasična vprašanja in praktični primeri.

## Dostop

Za vstop potrebuješ uporabniško ime in geslo, ki ju dobiš pri avtorju.

Vprašanja so v datoteki `questions.enc.json` šifrirana (AES-256-GCM, ključ iz uporabniškega imena in gesla prek PBKDF2). Brez pravilne prijave niso berljiva. Izvorne datoteke vprašanj niso del tega repozitorija.

Napredek (videna in zgrešena vprašanja) se shranjuje samo v brskalniku posamezne naprave.
