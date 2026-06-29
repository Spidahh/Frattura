# 09 - RIORGANIZZAZIONE CARTELLE

Questo file definisce come riorganizzare il progetto senza perdere niente.

Stato: schema vivo.
Data: 12-06-2026.

---

## Problema da risolvere

La cartella contiene:

- una direzione autore nuova;
- una story bible vecchia e contaminata;
- bozze scritte sulla vecchia trama;
- grafica legata sia ad atmosfera utile sia a simboli bocciati;
- archivio storico non canonico ma pieno di materiale da non dimenticare;
- strumenti tecnici per PDF.

Il problema non e' solo "dove stanno i file".
Il problema e' sapere che valore ha ogni file mentre si rifonda la saga.

---

## Nuova logica di lavoro

La cartella viene riorganizzata per stato, non per affetto verso i vecchi file.

### 1. Fonte viva

Sta in `_revisione/`.
Contiene:

- metodo;
- vincoli autore;
- decisioni;
- sintesi delle indicazioni rilette;
- inventario;
- audit;
- futuro canone rifondato.

### 2. Materiale da recuperare

Sta ancora nei suoi posti originali, ma viene letto attraverso l'inventario:

- `story_bible/`;
- `bozze/`;
- `grafica/`;
- `_archivio/`.

Non si sposta tutto fisicamente adesso per non rompere riferimenti, script e catene di lavoro.
Si riorganizza prima semanticamente: ogni file deve avere stato e uso.

### 3. Materiale tecnico

Sta in:

- `tools/`;
- `impaginato/`;
- asset tecnici di `grafica/impaginazione/`.

Non decide la storia.

---

## Struttura logica nuova

| Area logica | Cartelle/file attuali | Stato |
|---|---|---|
| Direzione autore | `00_LEGGIMI_DIREZIONE_FRATTURA.md`, `_revisione/02`, `_revisione/08` | fonte viva |
| Metodo professionale | `_revisione/00`, `_revisione/06`, `_revisione/11` | fonte viva |
| Decisioni | `_revisione/03` | fonte viva |
| Inventario e recupero | `_revisione/01`, `_revisione/04`, `_revisione/05`, `_revisione/10` | fonte viva |
| Vecchio canone | `story_bible/` | letto, contaminato, da trasformare |
| Vecchie bozze | `bozze/` | lette, contaminate, da recuperare per materiale |
| Archivio storico | `_archivio/` | letto, indicizzato, non canonico |
| Grafica | `grafica/` | parzialmente recuperabile |
| Riferimenti esterni/metodo | `riferimenti/` e `story_bible/riferimenti/` | supporto |
| Output e script | `impaginato/`, `tools/` | tecnico |

---

## Regole di riorganizzazione

1. Prima si classifica, poi si sposta.
2. Nessun file viene cancellato.
3. Nessun file viene archiviato senza una scheda di cosa contiene.
4. Il vecchio canone resta leggibile, ma viene disattivato come autorita'.
5. Le bozze restano leggibili, ma vengono disattivate come trama.
6. L'archivio resta consultabile e indicizzato.
7. Ogni nuova idea deve citare da quali materiali deriva.

---

## Fase attuale

Fase 1: riorganizzazione semantica.

Azioni:

- creare indice generale;
- creare inventario recupero;
- creare protocollo anti-perdita;
- aggiornare README e readme locali;
- completare audit;
- solo dopo decidere se spostare fisicamente file o cartelle.

Motivo:
spostare subito centinaia di file senza averli classificati bene aumenterebbe il caos.

---

## Fase successiva

Dopo audit completo:

1. creare nuova story bible pulita;
2. spostare vecchi file story bible in una sezione `materiale_vecchio_letto` oppure lasciarli con readme di disattivazione;
3. creare nuove cartelle canone per:
   - mondo;
   - misteri;
   - personaggi;
   - fazioni;
   - libri;
   - cronologia;
   - payoff;
4. aggiornare ogni rimando.

Questa fase si fa solo dopo approvazione della nuova premessa.

