# 13 - INDICE CANONE E ANTIRIDONDANZA

Questo file serve a impedire che i file guida si mangino tra loro.

Confine di uso:
- questo file governa la gerarchia dei file madre e derivati
- non decide contenuti nuovi
- serve a impedire ridondanza, rami paralleli e conflitti silenziosi

Per ogni tema grosso va chiarito:
- qual e' il file madre
- quali file derivano
- cosa non va duplicato

Uso rapido:
- apro questo file quando non so in quale documento scrivere o correggere una cosa
- se un tema compare in tre file diversi, qui devo trovare quale comanda
- se un file sembra doppione di un altro, la risposta va cercata qui prima di riscrivere

---

## 1. File madre per tema

| Tema | File madre | File di supporto |
|---|---|---|
| **Struttura profonda della saga** | `06_PROGRAMMAZIONE_GLOBALE.md` | `05_piano_espansione.md`, `00_scheletro_centrale.md` |
| **Timeline reale e pubblica** | `07_TIMELINE_E_RIVELAZIONE.md` | `09_TIMELINE_PERSONAGGI_E_ISTITUZIONI.md` |
| **Rivelazioni per libro** | `08_MATRICE_RIVELAZIONI.md` | `10_SORGENTI_DI_VERITA_E_ESPOSIZIONE.md`, `riferimenti/foreshadowing.md` |
| **Distribuzione dei segreti** | `12_MAPPA_SEGRETI.md` | `10_SORGENTI_DI_VERITA_E_ESPOSIZIONE.md`, `09_TIMELINE_PERSONAGGI_E_ISTITUZIONI.md` |
| **Consenso, folla, racconto pubblico** | `08_MATRICE_RIVELAZIONI.md` | `10_SORGENTI_DI_VERITA_E_ESPOSIZIONE.md`, `12_MAPPA_SEGRETI.md`, `09_TIMELINE_PERSONAGGI_E_ISTITUZIONI.md` |
| **Controllo Libro 1** | `15_MAPPA_CAPITOLI_LIBRO1.md` | `14_AUDIT_BOZZE_LIBRO1.md` |
| **Regole narrative** | `03_struttura.md` | `01_concept.md`, `riferimenti/voci_narrative.md` |
| **Lessico del mondo** | `04_glossario.md` | `02_magia.md` |
| **Patto e istituzioni** | `fazioni/patto_di_ferro.md` | `09_TIMELINE_PERSONAGGI_E_ISTITUZIONI.md` |
| **Antagonismi** | `personaggi/antagonisti.md` | `personaggi/censore_koss.md`, `personaggi/spettro_umano.md` |
| **Secondari** | `personaggi/secondari.md` | `09_TIMELINE_PERSONAGGI_E_ISTITUZIONI.md` |
| **Navigazione rapida** | `16_PERCORSO_RAPIDO.md` | `00_README.md`, `13_INDICE_CANONE_E_ANTIRIDONDANZA.md` |

---

## 2. Cose da non duplicare

### Il Prigioniero

Da definire bene solo in:
- `06_PROGRAMMAZIONE_GLOBALE.md`
- `personaggi/antagonisti.md`

Negli altri file:
- solo funzione locale
- niente nuove versioni dell'identita'

### Crosta / Culla

Da tenere come definizione piena in:
- `06_PROGRAMMAZIONE_GLOBALE.md`
- `07_TIMELINE_E_RIVELAZIONE.md`

Negli altri file:
- solo effetti, uso, lettura parziale

### Selene / Dorian / Kaelen finali

Gli esiti pieni stanno in:
- `06_PROGRAMMAZIONE_GLOBALE.md`

Le schede personaggio devono:
- allinearsi
- non riscrivere una seconda versione del finale

### Libri 1-7

La struttura lunga sta in:
- `05_piano_espansione.md`

Gli snodi obbligati di ogni libro stanno in:
- `05_piano_espansione.md`

La verifica di rivelazione sta in:
- `08_MATRICE_RIVELAZIONI.md`

L'audit dei rischi sta in:
- `11_AUDIT_LIBRI_E_BUCHI_FUNZIONALI.md`

Le timeline di mutazione stanno in:
- `09_TIMELINE_PERSONAGGI_E_ISTITUZIONI.md`

I canali giusti di consenso, folla e racconto pubblico stanno in:
- `10_SORGENTI_DI_VERITA_E_ESPOSIZIONE.md`
- `08_MATRICE_RIVELAZIONI.md`

Le mutazioni di massa, quartieri e istituzioni stanno in:
- `09_TIMELINE_PERSONAGGI_E_ISTITUZIONI.md`

### Libro 1 in bozze

La mappa di funzione capitolo per capitolo sta in:
- `15_MAPPA_CAPITOLI_LIBRO1.md`

L'audit di allineamento tra bozze e canone sta in:
- `14_AUDIT_BOZZE_LIBRO1.md`

Se si modifica una scena importante del Libro 1:
- si aggiorna prima la bozza
- poi si controlla se cambia la funzione in `15`
- poi si verifica se la diagnosi generale in `14` va stretta

---

## 3. Uso corretto dei file guida

Se devo:
- decidere il canone: `00_DECISIONI_APPROVATE.md`
- capire il cuore della saga: `00_scheletro_centrale.md`
- vedere il piano dei libri: `05_piano_espansione.md`
- vedere la storia vera lunga: `07_TIMELINE_E_RIVELAZIONE.md`
- controllare i segreti: `12_MAPPA_SEGRETI.md`
- controllare come rivelare: `10_SORGENTI_DI_VERITA_E_ESPOSIZIONE.md`
- controllare i buchi: `11_AUDIT_LIBRI_E_BUCHI_FUNZIONALI.md`
- controllare il Libro 1 scena per scena: `15_MAPPA_CAPITOLI_LIBRO1.md`
- controllare il Libro 1 come macchina complessiva: `14_AUDIT_BOZZE_LIBRO1.md`
- capire dove scrivere una correzione: `13_INDICE_CANONE_E_ANTIRIDONDANZA.md`

---

## 4. Regola finale

Se un tema grosso cambia:
1. si aggiorna il file madre
2. si aggiornano i file derivati
3. si controlla che non siano nate due verita' parallele

Sequenza minima corretta:
1. `06` per decisione finale
2. `07` per cronologia reale
3. `08` per emersione nel libro
4. `12` per chi sa o interpreta male
5. `10` per il canale di esposizione
6. solo dopo eventuali schede, audit o bozze

Nota di manutenzione:
- se nasce un nuovo file guida vivo, il suo posto gerarchico va dichiarato qui
