# CLAUDE.md — Manuale operativo del progetto "Frattura"
*Questo file viene caricato in automatico. È la mia bussola: dice dove vive cosa, come si lavora, cosa NON fare.*

## ⛔ CANCELLO — NON SCRIVERE NEMMENO UNA RIGA DI PROSA SENZA AVER FATTO QUESTO
*Ordine vincolante, non un consiglio. La prosa precedente è uscita sbagliata perché queste regole erano "suggerimenti". Adesso sono un cancello: se salti un passo, hai fallito, e il capitolo si **rifà da zero**, non si lucida.*

**Il segreto del mondo non si svela MAI in pagina.** Il lettore lo ricostruisce da solo, dopo. In pagina entra SOLO ciò che il POV vive, fraintende o considera normale. Esempi concreti PRIMA→DOPO (cosa è un leak e come si toglie) in `BIBBIA/04_COME_SCRIVERE.md` (§B).

**Tre passi obbligatori per OGNI capitolo:**
1. **PRIMA di scrivere:** compila la scheda anti-leak (`MANOSCRITTO/_TEMPLATE_CAPITOLO.md`, punti 1–9). Se la scheda mostra che il POV pensa/deduce la cosa giusta → la scena è sbagliata in partenza: rifalla prima di scrivere.
2. **MENTRE scrivi:** nessun POV deduce il meccanismo nascosto; nessun indizio viene commentato come "strano"; nessuna frase della LISTA NERA (sotto). Ancora ogni nome nuovo con un'etichetta di 2–3 parole alla prima comparsa.
3. **DOPO aver scritto:** esegui il QA anti-leak (`04_COME_SCRIVERE` §C). Se anche una sola risposta è sbagliata → **riscrivi**, non fare polish.

**LISTA NERA — se scrivi una frase di questo tipo, hai fallito (vale anche riformulata):**
- "come se sapesse dove andare" · "andò dritto, deciso, senza cercare" → il mostro NON sa, e tu non lo dici.
- "come un uomo torna a casa" · qualsiasi paragone che dà uno scopo o una meta al mostro.
- "erano già pronti" · "stava aspettando" · "era il tempo di chi era già pronto".
- "sapevano già dov'era" · "nessuno glielo indicò".
- "come chi spunta una voce su una lista" · "annuì soddisfatto" · gesti di un personaggio letti come conferma di un piano.
- "qualcuno aveva segnato il punto" · "prima ancora che cominciasse" · il POV che trova l'indizio e ne deduce la preparazione.
- "era strano che…" · "nessuno sapeva…" · "non aveva risposto" · qualsiasi cartello che dice al lettore cosa sospettare.

**Regola madre della lista: togli la deduzione, lascia il dettaglio nudo.** Il dettaglio resta in pagina (i tre graffi, i grigi calmi, i teli già piegati); la frase che lo spiega sparisce. Il collegamento lo fa il lettore, libri dopo.

## Cos'è il progetto
Saga **dark fantasy epico + mistero + avventura**, ~7 libri. Tono: ritmo, mostri, colpi di scena, verità a strati. **Mash-up**: si tiene tutto e si fa chiarezza; mondo complicato, tante sottostorie, molti personaggi. **Multi-POV "alla Lost"**: anche capitoli mono-personaggio; lo SFONDO (la macchina segreta) non si nomina mai, **trapela**.

## REGOLA ZERO — FABULA ≠ NARRAZIONE
Il file di canone `01_CANONE` (verità del mondo + storia + cronologia) contiene la **storia vera del mondo**: è materiale per l'autore/AI, NON la storia da mettere in pagina.

Nel manoscritto si narra la **superficie vissuta dai POV**. La macchina nascosta deve restare sepolta e funzionare sotto: entra solo come attrito, assenza, routine, gesto, conseguenza, dettaglio ambiguo. **Non trasformare mai il canone in pensieri dei personaggi, spiegazioni del narratore o domande esplicite del mistero.**

Metodo "alla Lost": il lettore deve trovare i segreti da solo e solo dopo poter ricostruire che c'erano. Un indizio riuscito sembra normale o quasi normale quando appare; non viene cerchiato con frasi tipo "era strano che", "nessuno sapeva", "qualcuno era già pronto", "non aveva risposto", "come se sapesse dove andare".

## STOP OPERATIVO — il metodo vale per OGNI capitolo nuovo
La **vecchia** bozza espansa (60 `cap-*.md`) fu **bruciata il 2026-06-26** perché col metodo sbagliato (leak **semantico**, non solo lessicale). Da allora il manoscritto è stato **riscritto da zero**: lo **stato reale** (quali capitoli esistono) è SEMPRE in `STATO.md` — non dare per scontato che "non ci sia prosa".

Operativamente: ogni **nuovo** capitolo passa dal CANCELLO qui sopra; i capitoli già scritti si rivedono col QA anti-leak (`BIBBIA/04_COME_SCRIVERE`), mai col polish della vecchia bozza. Nomi in `BIBBIA/GLOSSARIO.md`; scene per libro in `MANOSCRITTO/LIBRO_n/_OUTLINE.md`.

## Orientamento rapido (apri in quest'ordine)
1. `STATO.md` — dove siamo, cosa è fatto, **prossima mossa**.
2. `BIBBIA/00_INDICE.md` — mappa del canone (6 file).
3. `BIBBIA/04_COME_SCRIVERE.md` — voce + anti-leak + guardrail/**BOCCIATI**. Check a OGNI pezzo.
4. `BIBBIA/01_CANONE.md` — la **verità nascosta** del mondo (+ storia e cronologia).
5. `BIBBIA/03_STRUTTURA_E_MISTERI.md` — mappa misteri, outline, semi.

## Mappa della cartella (DOVE VIVE COSA)
| Cartella / file | Cos'è | Si tocca? |
|---|---|---|
| **`BIBBIA/`** | **IL CANONE** (6 file). Unica fonte viva. | Sì, qui si decide |
| `BIBBIA/00_INDICE.md` | mappa + tabella "fonti uniche" | Sì |
| `BIBBIA/01_CANONE.md` | verità del mondo, magia, movente/sorte, mondo, storia, cronologia | Sì |
| `BIBBIA/02_CAST.md` | tutti i personaggi: schede, intrecci, backstory, desiderio, regole di carattere | Sì |
| `BIBBIA/03_STRUTTURA_E_MISTERI.md` | struttura 7 libri, mappa misteri, outline, colpi di scena, tema, semi, continuità | Sì |
| `BIBBIA/04_COME_SCRIVERE.md` | voce, POV, ritmo + anti-leak (fabula≠narrazione, LISTA NERA, scheda+QA) + paletti/BOCCIATI | tienilo aperto mentre scrivi |
| `BIBBIA/GLOSSARIO.md` | nomi e termini **canonici** | Sì (prima di nominare) |
| `BIBBIA/_TEMPLATE/` | modelli (scheda personaggio, scheda luogo) | usa per creare |
| `BIBBIA/_DEPOSITO/` | file storici **assorbiti** | **No** (solo consultazione) |
| **`MANOSCRITTO/`** | **LA PROSA**: una cartella per libro (`LIBRO_1/cap-01_*.md`…) | Sì, qui si scrive |
| `00_METODO/` | libreria di tecnica narrativa | riferimento, non canone |
| `STATO.md` · `DECISIONI.md` · `DOMANDE_APERTE.md` | il **cruscotto** | Sì, aggiorna sempre |
| `FRATTURA.md` · `00_RIPRENDI_DA_QUI.md` | portali per l'umano | Sì |
| `_ARCHIVIO_*/` | **morto**, vecchie visioni | **MAI** usare come fonte |

## Come si lavora qui (workflow)
- **Una sola linea viva** = `BIBBIA/`. Le modifiche **sovrascrivono** il vecchio; niente versioni parallele.
- **A ogni pezzo, check `04_COME_SCRIVERE` §G**: è logico? è collegato? non è banale? il mistero resta nascosto (entra solo ciò che i personaggi percepiscono)?
- **Pensare → poi scrivere.** Prima il canone regge (`01_CANONE`), poi struttura/outline (`03_STRUTTURA_E_MISTERI`), poi prosa (`MANOSCRITTO`).
- **Quando decido qualcosa di nuovo:** lo scrivo SUBITO nel file giusto della BIBBIA **e** segno una riga in `DECISIONI.md` — ma solo dopo **OK esplicito dell'utente** (vedi sotto).
- **Quando trovo un buco / una scelta da fare:** la registro in `DOMANDE_APERTE.md`.
- **A fine sessione:** aggiorno `STATO.md`.
- **Nomi:** prima di battezzare un personaggio/luogo, controllo `GLOSSARIO.md` (per non creare doppioni o errori di ortografia).
- **Capitoli:** `MANOSCRITTO/LIBRO_n/cap-XX_titolo.md`; ognuno apre su una domanda/immagine e **chiude su un gancio**.

## Regole di collaborazione con l'utente (vincolanti)
- **Non registrare/decidere/agire senza un "ok" esplicito.** Ipotesi e scelte da menù NON sono decisioni confermate. In `DECISIONI.md` distinguo "confermata dall'utente" da "ipotesi non confermata".
- **Non generalizzare i feedback locali** ("non mi piace X *qui*" vale solo per quell'elemento).
- **Non "partire in quarta"**; tenere conto dell'INTERA conversazione; quando dice di fermarmi, fermarsi.
- **Meno domande a raffica, meno muri di testo; più sostanza.**

## Guardrail (la roba BOCCIATA — non riusare)
Vecchia base fuori: essere ferito che riassorbe; massa/creatura sotto la città **come motore**; rito per risvegliare la creatura; corpi fusi/sciolti/compattati; scambio di corpi; possesso semplice; nutrimento/batteria; debito/prezzo/chiavi; laboratorio come centro; mostro-professione; **loop/Prigioniero/Accordatore** (il LUOGO "Punto Zero" è invece riusato con senso nuovo, vedi `01_CANONE`); Ferro Silente/Cantori/pilastri viventi; Kaelen protagonista fisso; guerra poveri-ricchi o fazioni **come motore** (ok come sottotrame). Lista completa e viva in `BIBBIA/04_COME_SCRIVERE.md` (§G).
