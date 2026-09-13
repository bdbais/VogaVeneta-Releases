# Voga Veneta — download beta

Repository pubblico per il download delle versioni beta di **Voga Veneta**,
il simulatore didattico di voga alla veneta per Android.

## Installazione

1. Scaricare **[LATEST APK — ultima beta](downloads/VogaVeneta-latest.apk)**.
   Il collegamento punta direttamente al file da installare.
2. Aprire il file sul dispositivo Android e autorizzare l'installazione da
   questa fonte, se richiesto.
3. Al primo avvio conviene partire dalla **Scuola di voga**: nove lezioni
   brevi spiegano la postura, le mani sul remo, il premer e lo stalir.

Il gioco funziona senza rete. Serve il collegamento solo per la modalità
**Voga in due**, e il microfono solo se si vuole parlare con il compagno di
barca o gridare agli incroci ciechi.

## Requisiti

Android 6.0 o successivo, con supporto WebGL2 (praticamente tutti i telefoni
dal 2017 in poi). L'app si tiene in orizzontale.

<!-- CHANGELOG -->

## Barre orizzontali e comandi da mouse e tastiera — 0.1.0-beta13

- fiato ed equilibrio: barre orizzontali sul fianco sinistro, non piu' verticali sotto la manopola;
- da computer la modalita' arcade si comanda con W/Spazio, S, A/D e i pomelli si muovono da soli;
- in pro il giro della forcola si fa col mouse sull'ovale disegnato, anche al contrario per sciar;
- V passa da terza a prima persona.

### Verifica

- SHA-256 APK: `7220B48B7337955B1D1F323AC2123A7B3EE81D112FC17E17C8F20032D1DED827`
- SHA-256 certificato: `9f59ea07db424210233b45191f970677b3f89e219e56f4927b3ad70ff86dbdac`
- dimensione: 3.61 MB


## Onda che non urla piu, obiettivo che non copre, e si parte da dove vuoi — 0.1.0-beta12

- l'allarme ONDA scattava per la scia della tua stessa barca: adesso guarda avanti, avvisa una volta per barca che passa e solo se e' roba seria;
- il riquadro OBIETTIVO sta a sinistra sotto la tratta e dopo sette secondi si stringe su una riga;
- voga libera: si sceglie da dove partire, anche direttamente in Cannaregio o in Canal Grande;
- ogni tratta ha il suo cronometro e il suo record, con il passo confrontato in tempo reale;
- durante il varo lo schermo e' pulito: niente comandi sopra il filmato.

### Verifica

- SHA-256 APK: `1A29631F71EA02CD0EE49B7E8C52B3D24AF9E4A3A015BC18E5BD640779D805F5`
- SHA-256 certificato: `9f59ea07db424210233b45191f970677b3f89e219e56f4927b3ad70ff86dbdac`
- dimensione: 3.61 MB


## Modalita arcade, prima persona e varo con la gru — 0.1.0-beta11

- modalita ARCADE: due manopole, una spinge e una governa; classifiche separate da quelle PRO;
- in PRO si scia girando il pollice al contrario attorno alla forcola;
- pulsante per passare da terza a prima persona;
- si guarda attorno trascinando nella meta alta dello schermo;
- varo rifatto: la gru del pontile cala la barca in acqua, l'ormeggiatore sta sul molo.

### Verifica

- SHA-256 APK: `9F38BC4B98226FEFEFD2A861A13D0B53FC97873D40AD1ED6FAFC6BAE878933AE`
- SHA-256 certificato: `9f59ea07db424210233b45191f970677b3f89e219e56f4927b3ad70ff86dbdac`
- dimensione: 3.61 MB


## Comandi sotto la velocità — 0.1.0-beta10

- camera, microfono, radio e grida stanno in fila sotto il riquadro della velocità, fuori dalla zona dove si voga e lontani dall'ovale della forcola;
- l'icona delle comunicazioni sembrava il volume: ora è un fumetto con la Ó del richiamo, e la voce che attraversa l'acqua;
- il microfono era una emoji colorata, stonava in fila con le altre: ridisegnato a tratto;
- il riquadro dell'obiettivo copriva la riga di vento e marea: spostato più in basso.

### Verifica

- SHA-256 APK: `2934714920218B702B3E5E15D41FB47C1DA0514D5C4F78A4F15A2203D06E74D8`
- SHA-256 certificato: `9f59ea07db424210233b45191f970677b3f89e219e56f4927b3ad70ff86dbdac`
- dimensione: 3.60 MB


## Caricamento che arriva in fondo — 0.1.0-beta09

- l'avvio restava bloccato su «caricamento laguna»: la scena veniva costruita tutta in un blocco solo e il WebView si piantava. Ora si costruisce a fasi, cedendo il controllo fra una e l'altra;
- barra di avanzamento con percentuale, nome della fase e stima di quanto manca;
- se qualcosa si rompe in partenza adesso lo dice a schermo invece di girare a vuoto per sempre.

### Verifica

- SHA-256 APK: `A28C053D444485EC7E8FC8BF1B1EA64A78269BCC6FE026B66CD3D67E824C1373`
- SHA-256 certificato: `9f59ea07db424210233b45191f970677b3f89e219e56f4927b3ad70ff86dbdac`
- dimensione: 3.60 MB


## Remi in barca, vento vero, le grida e lo sterzo che si capisce — 0.1.0-beta08

- non si capiva come girare: l'ovale disegnato adesso è la rotta dritta — allarghi e accosti a destra, stringi e vai a sinistra — con la scritta sotto il comando che lo dice sempre;
- le onde erano alte due centimetri e invisibili: il riparo veniva contato due volte. Ora l'acqua si muove e si vede il moto ondoso arrivare;
- REMI IN BARCA: alzi il remo, ti siedi sul pagliolo e lasci passare l'onda. In piedi si cade, seduti no — ed è così che si fa davvero;
- il vento adesso frena a remare contro, fa orzare di traverso e da fermi ti porta via, insieme alla corrente di marea che scorre lungo il canale;
- le grida ai barcaroli: un tocco chiama Óoe, tenendo premuto scegli fra premi, stali, sia e longo. Chi ti sente rallenta;
- aggiornamento senza la finestra di sistema, dalla seconda volta in poi;
- se Android chiude l'app in secondo piano, al rientro si riprende dal punto in cui eri;
- sezione per offrire un caffè, nel menu e sul sito.

### Verifica

- SHA-256 APK: `D023CBBD90EBEE87CA1EB224114B59DCB481FE2CD207D6FFE2670F1EA87840A6`
- SHA-256 certificato: `9f59ea07db424210233b45191f970677b3f89e219e56f4927b3ad70ff86dbdac`
- dimensione: 3.59 MB


## Aggiornamento dentro l'app — 0.1.0-beta06

- all'avvio l'app controlla il manifesto pubblico e avvisa se c'è una beta nuova, con le novità;
- l'APK si scarica e si installa senza passare dal browser, con la barra di avanzamento;
- prima di installare si controlla che il pacchetto sia il nostro, non più vecchio, e con la stessa firma;
- se Android non ha ancora dato il permesso di installare da questa app, lo chiede e si riprova.

### Verifica

- SHA-256 APK: `4F9ED0F8902A338FEB3F9FE59B4ECB308F93E1935E8B8D97614259C4501875B4`
- SHA-256 certificato: `9f59ea07db424210233b45191f970677b3f89e219e56f4927b3ad70ff86dbdac`
- dimensione: 3.58 MB


## Audio che tace fuori dall'app, radio di bordo, l'ormeggiatore — 0.1.0-beta05

- uscendo dall'app il suono si spegne e la simulazione si ferma; al rientro riprendono da dove erano;
- il menu principale non veniva più tagliato sopra e sotto: su schermo orizzontale sta su due colonne;
- radiolina di bordo: un tocco cambia stazione, due la spengono, tenendo premuto esce la manopola con la scarica fra le stazioni;
- cinque stazioni, una per decennio dai Quaranta agli Ottanta, con musica strumentale originale generata dal gioco;
- al varo c'è l'ormeggiatore del pontile che dice cosa fare in ogni fase;
- spruzzo all'entrata in acqua e portatori che se ne vanno quando la barca galleggia;
- il microfono si chiude tornando al menu e quando l'app va in secondo piano.

### Verifica

- SHA-256 APK: `00ABF75823F88F921AB4E3ECB4B6C94DF67A15014A9FCE4A7EC1576842D6F3F0`
- SHA-256 certificato: `9f59ea07db424210233b45191f970677b3f89e219e56f4927b3ad70ff86dbdac`
- dimensione: 3.58 MB


## Barca a galla e tasti che rispondono — 0.1.0-beta03

- la barca galleggiava mezza affondata: il pescaggio era inventato, ora è calcolato sul dislocamento — un sandolo con dentro un uomo pesca cinque centimetri;
- il tasto HO CAPITO non rispondeva: cadeva nella metà destra bassa dello schermo, la zona da cui si voga, e il remo si mangiava il tocco;
- con una finestra aperta il remo adesso si ferma del tutto;
- varo rifatto: la barca la portano in quattro a mano, dai cavalletti fino all'acqua, con lo spruzzo all'entrata;
- la telecamera del varo non attraversa più i pali della tettoia.

### Verifica

- SHA-256 APK: `E5357EBF585F8B57CC73B1D5BD2B98FE430EC1142F05F279E75431D7D5321DC3`
- SHA-256 certificato: `9f59ea07db424210233b45191f970677b3f89e219e56f4927b3ad70ff86dbdac`
- dimensione: 3.57 MB


## Comandi e figura del vogatore — 0.1.0-beta02

- si voga da tutta la metà destra bassa dello schermo, non solo dentro l'ovale;
- il colpo si chiude da solo se stacchi il dito a metà ritorno;
- lo stalir ora governa davvero: senza, la prua scappa a sinistra di due gradi a colpo;
- il rematore ha spalle e collo, e la maglia a righe si vede;
- inquadratura da dietro la spalla riquadrata sul gesto;
- la lezione sta su due colonne quando il telefono è in orizzontale;
- niente banda bianca sotto il ritaglio dello schermo.

### Verifica

- SHA-256 APK: `FB2A198CC6E04F01B383B913DD7D86FF83932447A236A34E69454068CE69D1E2`
- SHA-256 certificato: `9f59ea07db424210233b45191f970677b3f89e219e56f4927b3ad70ff86dbdac`
- dimensione: 3.57 MB


## Prima beta giocabile — 0.1.0-beta01

- sandolo navigabile da San Giuliano a Rialto, con premer, stalir e sciàr;
- scuola di voga in nove lezioni, con i disegni del gesto;
- varo della barca: cavalletti, messa in acqua, imbarco, «molla la cima»;
- laguna con batimetria vera: canale segnato dalle briccole, secche e barene;
- moto ondoso calcolato: l'onda che vedi è quella che ti fa rollare;
- traffico con rotte di collisione, marea, vento, pioggia e càigo;
- quattro scafi da 1 a 6 remi, equipaggio IA, sartoria del vogatore;
- esame da gondoliere e prime corse turistiche;
- voga in due in rete con la voce, su Cloudflare.

### Verifica

- SHA-256 APK: `18761B865F0144D1F4B655837170D6BCCCC4E8226767B8DDB82D393B77D6DDCA`
- SHA-256 certificato: `9f59ea07db424210233b45191f970677b3f89e219e56f4927b3ad70ff86dbdac`
- dimensione: 3.57 MB

