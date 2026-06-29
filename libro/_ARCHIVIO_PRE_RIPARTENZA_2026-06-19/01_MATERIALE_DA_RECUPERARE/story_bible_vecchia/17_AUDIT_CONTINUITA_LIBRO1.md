# 17 - AUDIT CONTINUITA LIBRO 1

Questo file controlla la continuita' TESTUALE delle 42 bozze del Libro 1 contro il canone.

Confine di uso:
- non giudica la prosa, il ritmo o il gusto: quello resta lavoro di `14`
- non rifa' la mappa-funzione: quella e' `15`
- qui si controlla solo la coerenza concreta di: lessico, nomi, dettaglio fisico, cronologia/sapere, rispetto della matrice rivelazioni `08`, regole-madri `00`
- serve a stanare contraddizioni verificabili e ancorate a citazione, non impressioni

Le sei dimensioni controllate:
- `lessico` - termine usato col significato sbagliato o variante incoerente
- `nomi` - nome proprio o ruolo incoerente
- `fisica` - dettaglio fisico/scenico incoerente (lato del Marchio, oggetti, ferite, presenze)
- `cronologia` - rimando a eventi futuri o personaggio che sa qualcosa prima del dovuto
- `rivelazioni` - anticipo oltre il Libro 1 o errore residuo chiuso troppo presto
- `voce` - violazione regola-madre (Kaelen eroicizzato, spiegazione prima dell'attrito, POV rotto)

---

## 0. Nota di metodo (importante)

Questo audit e' stato prodotto leggendo capitolo per capitolo tutte le bozze e confrontandole con un estratto del canone (glossario `04`, decisioni `00`, matrice `08`, mappa `15`).

Poiche' l'estratto NON conteneva l'intera cartella `personaggi/` e `fazioni/`, una parte dei rilievi grezzi erano FALSI POSITIVI: termini e nomi segnalati come "non canonici" che in realta' sono definiti altrove nella bibbia. Sono stati verificati uno per uno e spostati nella sezione 3.

Restano quindi qui solo i rilievi reali, divisi in:
1. contraddizioni confermate (da correggere)
2. punti da verificare / giudizio d'autore
3. falsi positivi gia' esclusi (per non ricontrollarli)
4. manutenzione del canone consigliata

---

## 1. Contraddizioni confermate (priorita' alta)

> STATO SWEEP (2026-06-03): tutti e 5 i rilievi di questa sezione sono stati CORRETTI nelle bozze e in `libro_01_completo.md`.
> Termine scelto per la marca di Riven: `segnato` (braccio/polso segnato), distinto dal Marchio di Kaelen.
> Falsi nomi: "Mira" -> "Lena" (cap.13). "il Prigioniero" tolto dal cap.21 (Selene si ferma prima del nome).
> Residuo lasciato di proposito (giudizio d'autore, NON corretto): cap.42 riga finale "il Libro 1 smise di essere una fuga" - e' un'altra auto-citazione meta del narratore; la chiusura del libro, da decidere se tenerla come cornice voluta.

### 1.1 - Il Marchio sul lato DESTRO nel capitolo 36 [`fisica`, Alta]

E' il rilievo piu' grave e piu' certo.

- canone: il Marchio e' sul lato SINISTRO di Kaelen (polso/braccio sinistro), fissato nel cap.1 ("freddo gli morde il polso sinistro", "guardava solo il braccio. Il sinistro"). Confermato a sinistra anche in cap. 2, 4, 6, 7, 9, 10, 11, 18, 19.
- cap.36: > "Pianto' la mano destra sul ferro [...] e lascio' che il Marchio si affacciasse quel tanto che bastava a rendersi incompatibile."
- subito dopo: > "Il gelo gli morse la spalla. Le vene scure si accesero fino al polso." (dello stesso lato destro che ha fatto contatto)

Qui il Marchio agisce attraverso la mano/braccio destro: contraddice direttamente cap.1 e tutti gli altri capitoli.

Fix: portare il contatto sul braccio SINISTRO ("Pianto' la mano sinistra sul ferro..."). Se l'intento era far parare/toccare col braccio NON marchiato, allora il Marchio non deve "affacciarsi" da li': va esplicitata la distinzione (destro = arto normale, sinistro = Marchio).

### 1.2 - Il Marchio attribuito a Riven ("braccio/polso marchiato") [`lessico`/`fisica`, Alta]

Il Marchio e' un'anomalia ESCLUSIVA di Kaelen. Riven e' un Risonante deformato in infrastruttura: porta il "segno cenere"/indice lasciato dalla camera di scelta, NON un Marchio. In piu' capitoli il testo chiama "marchiato" il braccio/polso di Riven, conflando i due elementi-chiave:

- cap.31: > "Riven ebbe subito un tremito nel braccio marchiato." e > "Selene mise la mano sana sopra il polso marchiato." (di Riven)
- cap.38: > "Kaelen prende Riven da sotto. Tu gli tieni il braccio marchiato alto..." (il braccio e' di Riven) e > "inginocchiata sul polso di Riven, due dita sul segno cenere"
- cap.39: > "Selene si inginocchio' subito al suo fianco, due dita al polso marchiato..." (gesto rivolto a Riven)
- cap.41: > "...l'altra mano al polso marchiato." (di Riven) - istanza non rilevata dal workflow, trovata in verifica e corretta
- cap.33: il "segno cenere"/"marchio" su Riven usato in modo ambiguo accanto al Marchio di Kaelen

Fix di radice: scegliere UN termine dedicato per la marca di Riven (es. "segno cenere" oppure "indice") e non chiamarlo MAI "marchio"/"braccio marchiato". Cosi' la separazione Marchio (Kaelen) vs indice (Riven) resta netta. Vedi anche 4.2.

### 1.3 - Rottura della quarta parete nel capitolo 42 [`voce`, Alta]

Due frasi escono dalla finzione e misurano il tempo in unita' meta-narrative:

- > "Non c'e' stato da almeno dieci capitoli."
- > "Erano frasi da un libro peggiore."

Violano il POV interno richiesto da `00`. Fix: riferimenti interni alla finzione ("da quando siamo scesi"; "frasi da gente che si era gia' arresa").

### 1.4 - Anticipo di "il Prigioniero" nel capitolo 21 [`rivelazioni`, Alta]

- cap.21: > "Vuoi dire il Prigioniero?"

"Il Prigioniero" e' il nome in scena dell'entita' centrale di fine saga (`00`, `04`). Nominarlo apertamente nel Libro 1 anticipa un elemento riservato e chiude l'errore residuo previsto ("Non aprire" deve restare largo, vedi `15` cap.20-21).

Fix: togliere il nome. Selene non offre un nome ma reagisce al peso ("Non dire altro."), mantenendo l'ambiguita'.

### 1.5 - Anticipo di "Mira" nel capitolo 13 [`rivelazioni`, Alta]

- cap.13: Selene usa come falso nome "Mira", per giunta enfatizzato (> "usando proprio quel nome. Non a caso. Mai a caso.")

Mira e' un personaggio dei Libri 3-7 (`09`, `05`). Anche come falso nome, e specie se sottolineato, rischia di collidere/anticipare il cast futuro.

Fix: usare un falso nome qualunque non vincolato al canone futuro, senza evidenziarne il peso.

---

## 2. Da verificare / giudizio d'autore (priorita' media)

Questi NON sono errori certi: sono punti dove il testo sfiora un invariante e va deciso se e' voluto.

> STATO SWEEP (2026-06-03):
> - 2.1 APPLICATO: Marchio ancorato al lato sinistro nei cap. 18, 21, 25 (mantenendo la sensazione irradiata).
> - 2.3 APPLICATO (parziale): tolto il "riconoscimento" di verita' del Marchio al cap.41 (ora e' Kaelen a leggerci una conferma) e la "porta che si apre per accordo" al cap.23 (resa immagine opaca). Lasciato il lampo involontario del cap.4 (effetto subito, non potere).
> - 2.2 SCELTA: tenuto "crepa o porta" (cap.2) e "Porta" rotto di Riven (cap.21) come ambiguita' VOLUTE (il canone chiede l'errore "chiave" vivo ma non spiegato). Tolto solo l'uso piu' esplicito (cap.23).
> - GLOSSARIO `04` aggiornato con i termini mancanti (Ferro Silente, Martelli, Sindacato delle Scorie, Veyne Tal, Segno cenere/Indice, Continuita' portatile).
> - NON applicati di proposito (per non appesantire / per non spegnere la voce): 2.4 oggetti spariti (chiave inglese persa in fuga, tavoletta spezzata e abbandonata: plausibili senza spiegazione aggiunta), 2.5 deriva lessicale (registrata la spina in `04`, ma le varianti restano colore voluto), 2.6 Dissonante (la frase del cap.29 e' gia' comprensione esperienziale, non semplice etichetta).

### 2.1 - Il Marchio che si localizza al petto/costole/cuore [`fisica`, Media]

Il Marchio e' ancorato al polso/braccio sinistro, con cifra sensoriale freddo/gelo + ronzio. In tre capitoli la sensazione migra al torace:

- cap.18: > "il Marchio gli morse dietro il cuore."
- cap.21: > "il Marchio stringersi al centro del petto, dove non avrebbe dovuto avere mano."
- cap.25: > "il Marchio irrigidirsi nelle costole."

Se e' irradiazione voluta, ok; ma conviene ancorare comunque la sede al braccio sinistro almeno una volta per scena, per non perdere il dettaglio fisico fissato.

### 2.2 - Il Marchio descritto come "porta"/chiave [`rivelazioni`, Media]

Il canone vuole tenere VIVO l'errore "Marchio = chiave personale" ma senza esplicitarlo. Alcuni passaggi usano apertamente il lessico proibito:

- cap.2: > "se sei una crepa o una porta."
- cap.21: > "Non... nome. [...] Porta."
- cap.23: > "una porta che non si apriva per forza ma per accordo."
- cap.41: il Marchio che "risponde con riconoscimento del fatto che quella frase poteva essere vera"

Da soli sono sfumati e ammissibili come letture-possibili; il rischio e' la somma, che salda "porta" + "per cosa gli servi" in una rivelazione gia' chiarita. Decidere quanti tenerne.

### 2.3 - Il Marchio come capacita' percettiva (vicino alla Lettura di Selene) [`rivelazioni`, Media]

- cap.4: Kaelen, tramite il Marchio, "vide un lampo" di una scena del passato
- cap.41: il Marchio che "riconosce" una verita'

La Lettura (percepire residui, emozioni, frequenze) e' competenza di Selene. Attribuire al Marchio una percezione affidabile lo avvicina al "dono/strumento". Conviene mantenerlo come effetto involontario e costoso, non come potere investigativo.

### 2.4 - Oggetti di trama che spariscono [`fisica`, Media]

- la tavoletta di Selene: compare cap.16, si spacca al cap.22 ("raccolta spezzata e infilata alla cintura"), poi non e' piu' menzionata dal cap.23 in poi. Verificare se e' abbandonata di proposito.
- la chiave inglese di Kaelen (oggetto identitario, cap.1-4): sparisce dopo il cap.4 senza menzione. Decidere se persa/abbandonata nei livelli tecnici.

### 2.5 - Deriva lessicale sulla "continuita' portatile" [`lessico`, Media]

Il concetto centrale del carico agganciato a Riven e poi al gruppo e' chiamato con almeno 10 termini diversi tra cap.14 e 38: "ramo M-B", "movimentazione", "tampone mobile", "ramo di continuita'", "continuita' portatile", "ramo mobile", "quota mobile", "continuita' di trattamento", "il peso che stava portando", "compensazione".

Puo' essere evoluzione voluta del lessico, ma vale la pena fissare 1-2 termini stabili come spina dorsale (vedi 4.2).

### 2.6 - "Dissonante": etichetta vs comprensione [`sapere`, Bassa]

- cap.26: Selene riconosce Calix come "Dissonante" (termine gia' noto)
- cap.29: "Kaelen capisce per la prima volta cosa fosse un Dissonante"

Coerente solo se al 26 e' l'etichetta esterna e al 29 e' la comprensione esperienziale. Rendere esplicita la differenza dei due livelli.

---

## 3. Falsi positivi gia' esclusi (NON sono errori)

Verificati contro `personaggi/` e `fazioni/`. Tenuti qui per non ricontrollarli.

| Segnalato come... | In che capitoli | Verdetto | Prova nel canone |
|---|---|---|---|
| "Martelli/Martello" non canonico | 3, 4, 5, 13 | CANONICO | `fazioni/patto_di_ferro.md` ("Martelli \| Truppe con Sigilli"); `personaggi/dorian.md` ("Martello del Patto di Ferro") |
| "Ferro Silente" non canonico | 7, 8, 10, 13, 16, 22 | CANONICO | `02_magia.md` ("Ferro Silente \| Materiale raro \| Spegne temporaneamente Marchio"); citato anche in `15` |
| "Lucan" nome estraneo | 3, 4, 5, 8 | CANONICO | `personaggi/secondari.md` ("## Lucan"); `02_magia.md` ("Lucan \| Dominio") |
| "Varen" nome estraneo | 5 | CANONICO | `personaggi/secondari.md` ("## Varen \| Martello di ricognizione") |
| "Veyne/Veyne Tal" nome estraneo (refuso di Noma?) | 31, 32, 33, 35 | CANONICO | `personaggi/secondari.md` ("## Veyne Tal"); `10`, `12`. NON e' Noma |
| "Sindacato" non canonico | 8 | CANONICO | `personaggi/kaelen.md` ("Spurgatore del Sindacato delle Scorie"); `fazioni/altre_fazioni.md` |
| "Viandante" estraneo al Libro 1 | 10 | CANONICO e adatto al Libro 1 | `personaggi/antagonisti.md`; `05`; `08` (predazione, rottura di categoria nel Libro 1) |
| "Momento/Momenti" non canonico | 17 | CANONICO | glossario `04` ("Momenti"); `02_magia.md` |

Nota su 'Momento' (cap.17): canonico, MA `kaelen.md` fissa che Kaelen non ha MAI vissuto un Momento. Se il passaggio e' in POV-Kaelen, usarlo come metro interno e' un micro-stridore (lui non lo conosce in prima persona). Bassa priorita'.

---

## 4. Manutenzione del canone consigliata

### 4.1 - Registrare nel glossario `04` i termini gia' usati nel testo ma assenti

La maggior parte dei falsi positivi nasce perche' termini reali del mondo non sono nel glossario operativo `04`. Aggiungerli previene futura deriva e futuri falsi allarmi:

- `Ferro Silente` (rimando a `02_magia`)
- `Martelli` (rimando a `fazioni/patto_di_ferro`)
- `Sindacato delle Scorie` (rimando a `fazioni/altre_fazioni`; e' il datore di lavoro di Kaelen)
- `Veyne Tal` (rimando a `personaggi/secondari`)

### 4.2 - Fissare due termini-spina per evitare confusione col Marchio

Il problema 1.2 (Marchio attribuito a Riven) e 2.5 (deriva "continuita'") si risolvono alla radice fissando il lessico:

- la marca lasciata dalla camera su Riven = sempre `segno cenere` (o `indice`), MAI "marchio"
- il carico mobile agganciato a Riven/gruppo = scegliere 1-2 termini stabili (es. `continuita' portatile` + `ramo`) come spina dorsale, lasciando le altre varianti solo come colore occasionale

---

## 5. Quadro sintetico per capitolo

Solo rilievi reali (esclusi i falsi positivi della sez. 3). C = confermato, V = da verificare.

| Cap | Rilievi |
|---|---|
| 1 | pulito |
| 2 | V "crepa o porta" (2.2) |
| 3 | pulito (Martello/Lucan = falsi positivi) |
| 4 | V Marchio come lampo percettivo (2.3) |
| 5 | pulito (Lucan/Varen = falsi positivi) |
| 6 | pulito |
| 7 | pulito (Marchio Bianco come luogo: vedi nota) |
| 8 | pulito (Sindacato = falso positivo) |
| 9 | pulito |
| 10 | pulito (Viandante/Ferro Silente = falsi positivi) |
| 11 | pulito |
| 12 | pulito |
| 13 | **C** anticipo "Mira" (1.5) |
| 14 | pulito |
| 15 | V barella spiegata troppo come "correzione" (15 in `08`) |
| 16 | pulito |
| 17 | pulito ("Momento" = falso positivo; vedi nota 3) |
| 18 | V Marchio "dietro il cuore" (2.1) |
| 19 | pulito |
| 20 | pulito |
| 21 | **C** anticipo "il Prigioniero" (1.4); V Marchio al petto (2.1); V "Porta" (2.2) |
| 22 | V tavoletta che poi sparisce (2.4) |
| 23 | V "porta che si apre per accordo" (2.2) |
| 24 | V Marchio = solo "sollievo" senza cifra freddo/ronzio (2.1) |
| 25 | V Marchio "nelle costole" (2.1) |
| 26 | pulito |
| 27 | pulito |
| 28 | pulito |
| 29 | V "Dissonante" etichetta vs comprensione (2.6) |
| 30 | pulito |
| 31 | **C** "braccio/polso marchiato" su Riven (1.2) |
| 32 | pulito |
| 33 | **C** "segno cenere/marchio" ambiguo su Riven (1.2); V lato Marchio non ancorato |
| 34 | pulito |
| 35 | pulito (Veyne = falso positivo) |
| 36 | **C** Marchio sul lato DESTRO (1.1) |
| 37 | V "segno cenere" usato per il Marchio di Kaelen (2.5/4.2) |
| 38 | **C** "braccio marchiato"/"segno cenere" su Riven (1.2) |
| 39 | **C** "polso marchiato" su Riven (1.2) |
| 40 | pulito |
| 41 | V Marchio che "riconosce" verita' (2.3) |
| 42 | **C** rottura quarta parete (1.3) |

Nota su "Marchio Bianco come luogo" (cap.7, 12): alcuni passaggi usano "Marchio Bianco" come destinazione fisica ("usciamo al Marchio Bianco"), mentre `04`/`15` lo trattano come apparato/linguaggio di controllo. Da decidere se nel parlato dei personaggi e' tollerato come metonimia di luogo o se va distinto. Priorita' bassa.

---

## 6. Diagnosi finale

Il Libro 1 e' molto coerente sul piano della continuita' testuale. Su 42 capitoli:
- 5 contraddizioni confermate da correggere (di cui 2 di radice lessicale: lato Marchio e Marchio-su-Riven)
- alcuni punti di giudizio d'autore concentrati su un solo nodo ricorrente: la fenomenologia del Marchio (sede, "porta", percezione)
- nessuna incoerenza grave di trama, cronologia o ruoli

Il lavoro piu' utile e' chirurgico:
1. uniformare il lato del Marchio (sempre sinistro) e separare nettamente Marchio (Kaelen) da segno cenere/indice (Riven)
2. togliere i due anticipi (Mira, il Prigioniero) e la rottura di quarta parete
3. registrare in `04` i termini gia' vivi nel testo

Nota di manutenzione:
- se si correggono i capitoli 31/33/36/38/39 sul Marchio, aggiornare anche `15` se cambia la funzione percepita
- questo file va rigenerato dopo uno sweep di correzione per verificare che i fix non introducano nuove derive
