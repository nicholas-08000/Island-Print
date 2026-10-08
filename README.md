# Island Print — materiale recuperato

Recuperato dalla conversazione condivisa su claude.ai
(https://claude.ai/share/ef8a703a-9b61-4d47-a085-4983d1c6d2db).
La conversazione si interrompe durante il rebranding del sito portfolio.

## 1. Contesto

- Agenzia attuale: **VBD Digital Studios**. Tre ragazzi in Sardegna.
- Clienti: piccole aziende locali, acquisiti col passaparola. Obiettivo: espandersi.
- Servizi: siti web, gestione social, sponsorizzate; in futuro e-commerce.
- Punti di forza: prezzo e rapporto umano, risposte rapide.
- Richiesta: un nome distintivo e brandizzabile, che si stacchi da "web design".
  Lingua libera (italiano, sardo, misto, inglese, inventato).

## 2. Opzioni di nome proposte

| Direzione | Nomi |
|---|---|
| Sardo | Pintadera, Nuraxi, Janas, Ajò, Bentu, Luxi, Domu, Mastru |
| Misto sardo/italiano | Domu Digitale, Pintadera Studio, Ajò Lab, Bentu Creativo, Nuraxi Digitale |
| Italiano | Trama, Impronta, Faro, Bottega, Scintilla, Vivida |
| Inglese | Granite, Mistral, Saltwork, Coral, Island Made, Kiln |
| Inventati | Vibd, Nurà, Pintà, Janu |

Preferiti di Claude: Pintadera, Ajò, Vivida.

### Opzioni "isola"

- Sardo: Ìsula, Isulanu
- Italiano: Approdo, Arcipelago, Rotta, Insulae
- Inglese: Islandmark, Islander, Isle & Co.
- Inventati: Isolab, Islabs, Isùla

Preferiti: Ìsula, Approdo, Isolab.

### Verifiche consigliate prima di scegliere

Dominio .it e .com, social (Instagram/Facebook), marchio su UIBM ed EUIPO,
test del telefono (dirlo a voce e farlo scrivere), ricerca Google.

## 3. Island Print

Nome proposto da voi. Idea: **Island** = le origini sarde, **Print** = impronta,
cioè lasciare un segno riconoscibile (lo stesso concetto della pintadera).

Rischi segnalati:
1. "Print" si legge "stampa": i clienti locali possono pensare a una tipografia.
2. Due parole inglesi comuni sono difficili da registrare come marchio e da
   posizionare su Google ("island print" indica anche le stampe tropicali).

Alternative che tengono il concetto: **Islandmark**, **Island Imprint**,
**Isola Pintadera**, **Island Footprint**.

### Come far capire che è "impronta"

1. Logo con l'impronta digitale a forma di Sardegna (scelta consigliata);
   alternative: orma sulla sabbia, motivo della pintadera.
2. Claim fisso: "Lasciamo il segno, online." / "Il vostro segno nel digitale." /
   "Un'impronta che si ricorda." / "Siti e social con la vostra impronta."
3. Storia del nome: "Island perché siamo nati in Sardegna. Print perché ogni
   progetto deve lasciare un'impronta riconoscibile, come quella di un dito: unica."
4. Linguaggio interno: i progetti sono "impronte", il portfolio è "Le nostre
   impronte", la call iniziale è "Lasciamo il primo segno".
5. Opzionale: scrivere Islandprint attaccato.

## 4. Logo

Creato come artifact su claude.ai (privato) con due tavole:
- **Logo principale**: impronta digitale con le creste che seguono la costa
  sarda. Il centro del vortice cade nel cuore dell'isola, alcune linee sono
  interrotte per renderla più realistica. Accanto: "Island Print." con il
  claim "Lasciamo il segno, online."
- **Varianti**: versione chiara su blu petrolio, icona per profilo/app, prova a
  dimensione piccola, palette **blu petrolio, corallo, sabbia**. Marchio SVG in
  due spessori (quello spesso per le dimensioni piccole).

Dettaglio storico per il racconto: i Greci chiamavano la Sardegna **Ichnusa**,
da *ichnos* = "orma/impronta". Island Print è la traduzione moderna del nome
antico.

Nota: il contorno dell'isola era ricostruito a mano da coordinate, quindi
approssimato. Per la versione definitiva va ripassato su una mappa precisa.

Immagini recuperate (PNG, 1200x720):
- `logo/logo-principale.png`
- `logo/varianti-e-palette.png`

Vettoriali originali (recuperati dagli zip esportati):
- `logo/svg/marchio-blu-sottile.svg`, `marchio-blu-spesso.svg` (#0E3B43)
- `logo/svg/marchio-corallo-spesso.svg` (#D9573B)
- `logo/svg/marchio-sabbia-sottile.svg`, `marchio-sabbia-spesso.svg` (#F4EFE6)
- `logo/varianti-e-icona.pdf`: tavola delle varianti
- `sorgenti/landing-storia/Storia.dc.html`: la landing page della storia del brand (testi e stili completi)
- `sorgenti/`: i mockup HTML esportati (`Main.dc.html`, `Varianti.dc.html`) con le misure di font, spazi e colori. Le librerie React incluse negli zip non sono state copiate.

Spesso (stroke 16) per le dimensioni piccole, sottile (stroke 9) per le grandi.

## 5. Landing page di storia del brand

Artifact aggiunto alla stessa tela. Struttura:
1. **Il nome antico**: "Ichnusa" in grande.
2. **Il segno**: dall'orma all'impronta digitale. Tre schede: la costa è la
   prima linea, il centro è nel cuore dell'isola, le linee interrotte lo
   rendono inimitabile.
3. **Il nome dell'agenzia**: "Island, perché è casa. Print, perché resta."
4. **Cosa fate**: siti, social, sponsorizzate, e-commerce (etichetta "presto");
   punti di forza: risposte rapide, prezzi chiari, persone e non ticket.
5. **Chi siamo**: "tre ragazzi, un'isola, troppi siti brutti".
6. **Chiamata finale**: "Qual è la tua impronta?" con email e WhatsApp.

Foto, nomi, ruoli, email, WhatsApp e partita IVA erano segnaposto tra parentesi quadre.

## 6. Repository portfolio (VBD Digital Studios)

Repository GitHub sull'account `nicholas-08000`, probabilmente `Repository2`.
Non è nello scope di questa sessione.

- Frontend React + TypeScript, backend FastAPI, MongoDB per le richieste del form.
- Sezioni: hero "Tre menti. Una visione digitale.", chi siamo, approccio,
  progetti (Hair Studio, Portoscuso Mare, La Vecchia Tonnara, Mjolnir), case
  study, servizi, perché noi, numeri, processo, contatti, footer.
- Quasi tutti i testi sono in `frontend/src/data/site.ts`.
- Grafica attuale: logo VBD con gradiente blu-viola, accento `#1E4FD8`.
- Da fare: email di destinazione del form ancora di test; email e WhatsApp
  segnaposto.

## 7. Dove si era interrotto

Rebranding del portfolio in Island Print (logo a impronta, palette blu petrolio
e corallo, storia dell'Ichnusa). Claude aveva letto `site.ts`, `index.css`,
Hero, Navbar, Footer e `index.html` quando la risposta è stata interrotta.
Nessuna modifica era stata applicata.
