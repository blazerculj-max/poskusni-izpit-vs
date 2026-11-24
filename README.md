# Poskusni izpit VS

Spletna aplikacija za pripravo na izpit za trženje enot vzajemnih skladov (ATVP).

**Stran:** https://blazerculj-max.github.io/poskusni-izpit-vs/

## Kaj ponuja

- **Poskusni izpit:** 40 vprašanj po razporeditvi pravega izpita (8/8/8/4/4/4/4) in 60 minut časa. Najprej se izberejo vprašanja, ki jih še nisi videl. Na koncu dobiš rezultat po sklopih in pregled odgovorov z razlagami.
- **Vadba po sklopih:** brez časovne omejitve. Po vsakem odgovoru takoj vidiš rešitev in pojasnilo.
- **Na začetno stran:** gumb z ikono hiške je na vsakem zaslonu. Med izpitom pred izhodom vpraša za potrditev; prekinjen izpit ni ocenjen.
- **Današnja vaja:** 15 vprašanj (okoli 10 minut) – zgrešena vprašanja, ki so spet na vrsti (ponavljanje čez 1, 3, 7, 14 in 30 dni), nekaj iz najšibkejšega sklopa in nova.
- **Ugibam:** ob vprašanju lahko označiš, da ugibaš; pravilno uganjena vprašanja gredo med zgrešena za ponovitev (tipka U).
- **Od napake do lekcije:** ob razlagi je povezava na ustrezno lekcijo s kratkim povzetkom, rezultat pa priporoči lekcije, kjer se je nabralo največ napak.
- **Zgrešena vprašanja:** napačno odgovorjena vprašanja se shranijo za ponovitev.
- **Učitelj:** 83 lekcij po vrstnem redu prosojnic (razlaga, zapiski, pasti za izpit, primeri) z vprašanji za preverjanje. Osem lekcij ima animirane razlage po korakih ali drsnike (postopno varčevanje, presečna ura in izplačilo, združitev skladov, pot borznega posla, sporočanje Uradu, davčne stopnje po letih, dvojno obdavčenje, trikotnik prevare). V Claude verziji še AI učitelj, ki razlaga, sprašuje in bere na glas.
- **Dril »drži / ne drži«:** vsaka trditev iz banke posebej, s takojšnjo rešitvijo in pojasnilom; najprej pridejo zgrešene in nevidene trditve.
- **Učna gradiva:** miselni vzorci za vseh 7 sklopov, sheme v lekcijah, pregled rokov in zneskov z iskanjem, primerjalne tabele, kartice za ponavljanje in infografika za vsak sklop.

Banka obsega 843 vprašanj iz gradiv vseh sedmih sklopov, preverjenih ob originalnih gradivih. Večina jih ima najprej oštevilčene trditve, nato kombinirane odgovore (npr. »samo 2«, »1, 2 in 4«, »vse razen 3«). Druga so klasična vprašanja z odgovori A–D in praktični primeri. Nekatera vprašanja imajo »dvojčka« v drugi obliki (A–D in trditve); v istem izpitu ali vaji se nikoli ne pojavita oba. Računskih vprašanj je malo (pravi izpit jih skoraj nima in kalkulator ni dovoljen): na izpitu je največ eno, pa še to le v približno vsakem tretjem, v vaji največ dve na začetku seta.

## Dostop

Za vstop potrebuješ uporabniško ime in geslo, ki ju dobiš pri avtorju.

Vprašanja so v datoteki `questions.enc.json` šifrirana (AES-256-GCM, ključ iz uporabniškega imena in gesla prek PBKDF2). Brez pravilne prijave niso berljiva. Izvorne datoteke vprašanj niso del tega repozitorija.

Napredek (videna in zgrešena vprašanja) se shranjuje samo v brskalniku posamezne naprave.
