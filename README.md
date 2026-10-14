# AF Alessandro Flaminio · sito demo (FICO)

Sito vetrina statico per il salone di Via Paolo Sarpi 52 a Milano: HTML, CSS e JS vanilla, senza dipendenze e senza build. Le uniche risorse esterne sono i font Instrument Serif e Hanken Grotesk da Google Fonts e la mappa Google, che si carica solo quando l'utente clicca.

## Avvio in locale

```bash
cd alessandro-flaminio
python3 -m http.server 4319
```

Poi apri http://localhost:4319. Il sito si può pubblicare così com'è su Vercel, Netlify o GitHub Pages.

## Struttura

- `index.html`: pagina unica. Sezioni: Hero, Il salone (con titolare e staff), Servizi, Lavori (galleria con lightbox), Dicono del salone, Orari e contatti (mappa caricata al clic), Footer
- `css/style.css`: design system (token colore, tipografia), layout responsive, stati hover e focus, `prefers-reduced-motion`
- `js/main.js`: header compatto, menu mobile, stato "aperto ora" calcolato sull'ora di Milano, evidenziazione del giorno corrente, mappa su richiesta, lightbox (tastiera e swipe), comparsa delle sezioni
- `images/`: foto in JPG e WebP (due misure quando la risoluzione lo permette), logo AF, logo FICO
- `favicon.svg` (monogramma "AF" nel colore del logo) e `apple-touch-icon.png` (dal logo ufficiale)

## Direzione creativa

- **Palette**: la prugna del logo AF (`#7A2A69`) come unico accento; un bianco latte caldo, ripreso dal pavimento chiaro del salone, come fondo; un inchiostro quasi nero, ripreso dalle poltrone. Niente nero e oro.
- **Tipografia**: Instrument Serif, un serif editoriale con un corsivo morbido, per i titoli; Hanken Grotesk per i testi.
- **Composizione**: titoli grandi, sezioni numerate e foto di formati diversi accostate come in una rivista. Nella galleria i confronti "prima/dopo" non vengono mai ritagliati, così le etichette restano leggibili.
- **Titolo hero**: "Capelli sani, belli e alla moda" riprende la frase del vecchio sito ufficiale ("una chioma sana, bella e alla moda").

## Fonti (consultate il 14/10/2026)

1. Scheda Google Maps "Alessandro Flaminio", Via Paolo Sarpi 52 (CID 3250997063806345002): dati, 5 foto, recensioni
2. Vecchio sito ufficiale `miglioriparrucchieri.milano.it`, oggi offline e letto tramite Wayback Machine (pagine "Chi siamo", "Contatti" e home, 2018–2021)
3. Instagram ufficiale [@afalessandroflaminio](https://www.instagram.com/afalessandroflaminio/): la bio indica entrambe le sedi (Via G. Fara 14 e Via Paolo Sarpi 52) e "Chiamaci e prenota"
4. Facebook "AF alessandro flaminio" (trovato con una ricerca, contenuti non letti perché serve l'accesso)
5. `alessandroflaminio.com`: online, ma è una pagina modello del 2016 senza contenuti (solo un testo di benvenuto generico e tre miniature da 140–280 px). Non è stato usato
6. Treatwell "A.F. Alessandro Flaminio - Via Gustavo Fara": riguarda **solo l'altra sede**, perciò non è stato usato per prezzi e orari

### Dati verificati

| Dato | Valore | Fonti |
|---|---|---|
| Indirizzo | Via Paolo Sarpi 52, 20154 Milano | Google Maps, sito ufficiale, Instagram |
| Telefono | 02 312940 | Google Maps, sito ufficiale |
| Orari | Mar–Ven 9:30–18:00 · Sab 9:00–18:00 · Dom e Lun chiuso | Google Maps; identici sul sito ufficiale |
| Categoria | Salone da parrucchiere, per donna e per uomo | Google Maps, sito ufficiale ("acconciature unisex") |
| Accessibilità | Ingresso accessibile in sedia a rotelle | Google Maps |
| Seconda sede | Via Gustavo Fara 14 | Sito ufficiale, Instagram |
| Prodotti | Goldwell (poster in salone in una foto del 2023, foto di formazione Kao/Goldwell su Instagram), Farmavita (sito ufficiale e Treatwell Fara) | |
| Prenotazione | Telefonica ("Chiamaci e prenota", bio Instagram) | |
| Servizi | Tagli, acconciature anche da sposa, colorazioni, colpi di sole, decolorazioni, trattamenti tricologici e ristrutturanti, cheratina, stirature, permanente, extension | Sito ufficiale (2018); schiariture/balayage, biondi ed extension anche nei post Instagram 2025 |
| Titolare | Alessandro Flaminio: studi in accademia, titolo di maestro d'arte, anni di insegnamento | Sito ufficiale ("Chi siamo") |
| Formazione dello staff | Corsi di aggiornamento | Risposta del titolare a una recensione Google |

### Informazioni volutamente non pubblicate

- **Prezzi**: non esiste un listino della sede Sarpi. I prezzi Treatwell sono della sede di Via Fara e le promozioni a 10 € del sito ufficiale sono del 2018 e riguardavano solo Via Fara
- **Ingresso libero senza appuntamento** (sito ufficiale 2018): in contrasto con l'attuale "Chiamaci e prenota" su Instagram, quindi omesso
- Superficie (60 mq), 8 postazioni e 4 lavatesta: dati del 2018, forse superati
- Nomi e numero dei collaboratori: nessuna fonte aggiornata
- Valutazione media Google (4,6 su 36 recensioni a oggi): è un dato che cambia, quindi non è stato riportato
- Buoni regalo (sito 2018): non confermati oggi
- Email `info@alessandroflaminio.com` (sito 2018): il dominio è ancora attivo e ha la posta configurata, ma non si sa se la casella sia usata oggi. Si può aggiungere al sito dopo la conferma del titolare

### Da confermare con il titolare

- Elenco dei servizi attivi oggi nella sede Sarpi, in particolare extension, acconciature sposa, permanente e trattamenti alla cheratina
- Marchi usati oggi in salone (Goldwell e Farmavita, oppure anche L'Oréal, Matrix e Framesi come nel 2018)
- Se vuole mostrare la sede di Via Fara in modo più completo (ora c'è una sola riga)
- Testo sul titolare: è una rielaborazione del suo "Chi siamo" del 2018
- Se è disponibile un sistema di prenotazione online anche per Via Sarpi
- Se il dominio `alessandroflaminio.com` può ospitare il nuovo sito (oggi mostra una pagina modello del 2016)
- Nome commerciale preferito: "AF Alessandro Flaminio", "Alessandro Flaminio" o "AF Parrucchieri" (tutti e tre compaiono sui suoi canali)
- Su Google Maps esiste un'altra scheda, "Flaminio Alessandro", in un punto diverso (probabilmente la sede di Via Fara). Non è stata usata

## Foto

| File | Soggetto | Fonte |
|---|---|---|
| salone-sarpi-interno-postazioni | Interno con vetrina sul fondo (hero) | Google Maps, foto dell'utente "grazia tardugno", mar 2023 |
| salone-sarpi-specchi-luci | Postazioni e specchi illuminati | Google Maps, "grazia tardugno", dic 2022 |
| salone-sarpi-vetrina-prodotti | Scaffale con prodotti vicino all'ingresso | Google Maps, "grazia tardugno", dic 2022 |
| lavoro-capelli-lunghi-onde | Cliente con capelli lunghi mossi, poster Goldwell sullo sfondo | Google Maps, "grazia tardugno", feb 2023 |
| staff-salone-sarpi | Selfie di tre parrucchiere in salone (942×476, bassa risoluzione) | Google Maps, "grazia tardugno", mar 2023 |
| lavoro-biondo-capelli-lunghi | Biondo, capelli lunghi | Instagram @afalessandroflaminio, post DJrWmgNqQNV (15/05/2025) |
| lavoro-schiariture-prima-dopo | Schiariture, prima e dopo | Instagram, post DJmYUv7KqKF (13/05/2025) |
| lavoro-extension-prima-dopo | Extension, prima e dopo | Instagram, post DI1cds9ixoL (24/04/2025) |
| lavoro-extension-volume-prima-dopo | Extension, prima e dopo | Instagram, post DG3dX0Tizzp (06/03/2025) |
| logo-af-alessandro-flaminio | Logo AF (cerchio prugna) | Foto profilo Instagram, 150 px |

Note:
- Le 4 foto Instagram hanno pareti in mattoni a vista, che non si vedono nelle foto della sede Sarpi: sono quasi certamente lavori della sede di **Via Fara**. Sul sito sono presentate come lavori "pubblicati da AF Alessandro Flaminio", senza indicare la sede
- Le foto Instagram sono disponibili solo a 640 px. Per una versione definitiva servono gli originali
- Le didascalie (biondo, schiariture, extension) riprendono il testo dei post ufficiali
- Non sono state usate foto stock, immagini generate o immagini di altri saloni. Esclusi: le anteprime dei reel (bassa risoluzione, con testo sovrimpresso) e le foto di eventi e formazione (Kao Salon Academy, Goldwell Color Sphere)
- I metadati EXIF/XMP sono stati rimossi da tutte le immagini: con `cwebp -metadata none` per i WebP, eliminando i segmenti APP1/APP13 per i JPG

### Autorizzazioni da ottenere prima della pubblicazione

- Il permesso del titolare per tutte le foto e per il logo
- Le foto Google Maps sono state caricate dall'utente "grazia tardugno", che potrebbe far parte dello staff: serve il suo consenso, oppure foto equivalenti scattate dal salone
- Il consenso delle persone ritratte: le clienti nei lavori e le tre parrucchiere nel selfie
- Il consenso degli autori delle recensioni citate (testi brevi e attribuiti, presi da recensioni pubbliche su Google)

## Funzionalità

- Telefono `tel:+3902312940` (header, hero, servizi, contatti, footer, barra rapida su smartphone)
- Indicazioni con Google Maps (`/maps/dir/?api=1`)
- Mappa incorporata che si carica solo dopo il clic (privacy: niente cookie Google prima del consenso implicito dell'utente)
- Stato "Aperto ora / Chiuso ora" e giorno corrente evidenziato
- Link a Instagram e Facebook
- Lightbox della galleria (frecce, Esc, swipe)
- Non ci sono moduli di contatto né sistemi di prenotazione simulati

## Test eseguiti

- Desktop 1440×900 e smartphone 375×812 nel browser integrato
- Nessun errore in console, nessuna immagine rotta, nessuno scroll orizzontale
- Menu mobile, ancore interne, lightbox, caricamento della mappa e link `tel:` verificati
- **Errore corretto**: su smartphone il menu si apriva senza sfondo, perché il `backdrop-filter` dell'header fa da contenitore agli elementi `position: fixed`. Il pannello ora è posizionato rispetto all'header
- Footer: riporta esattamente "Website designed by FICO", con link email a FICO

## Privacy e note legali

- Il sito non usa cookie propri né strumenti di analisi
- Google Fonts e la mappa Google sono servizi di terze parti. Per una pubblicazione definitiva conviene ospitare i font in locale e aggiungere un'informativa privacy e cookie
- Prima di pubblicare servono partita IVA e ragione sociale nel footer (l'obbligo vale per i siti di attività commerciali): vanno chiesti al titolare
