# Comuni italiani: CAP, PEC e codici ISTAT (Veneto, CSV gratuito)

Elenco aggiornato dei comuni del **Veneto** con **CAP** (anche per i comuni con più CAP),
**PEC**, email e indirizzo del municipio, **codice ISTAT**, **codice catastale**, codice fiscale,
provincia e regione. In CSV, pronto da importare.

Dati aggiornati al **27 settembre 2026**: 559 comuni, 649 coppie comune/CAP,
7 province. Il file è rigenerato ogni mese dalle fonti ufficiali.

**Tutta Italia (quasi 7.900 comuni), in CSV, Excel, JSON e SQL, con frazioni, coordinate,
superficie, popolazione e CAP per via: [comunidb.it](https://comunidb.it/#prezzi).**

## File

| File | Contenuto |
|---|---|
| `csv/comuni.csv` | Un comune per riga: codici, provincia, regione, CAP principale, `multi_cap`, PEC, email, indirizzo e sito del comune |
| `csv/cap.csv` | Tutte le coppie `codice_istat`–`cap`: i comuni con più CAP hanno una riga per CAP |
| `csv/province.csv` | Le province del Veneto, con il numero di comuni |
| `csv/regioni.csv` | La regione, con il numero di province e di comuni |
| `ATTRIBUZIONI.txt` | Fonti e licenze |

I CSV sono in UTF-8 con BOM (si aprono correttamente in Excel) e separati da virgola. I codici
(ISTAT, CAP, provincia, regione) sono testo: mantengono gli zeri iniziali.

Le schede di ogni comune e di ogni CAP si consultano gratis su [comunidb.it](https://comunidb.it).

## Fonti e licenze

- **ISTAT** (elenco dei comuni SITUAS): CC BY 4.0.
- **IndicePA** (AgID): PEC, email, indirizzo, sito web. CC BY 4.0.
- **OpenStreetMap**: CAP dei comuni con più CAP. © OpenStreetMap contributors, ODbL 1.0: la
  tabella `cap.csv` resta sotto ODbL e si può ridistribuire alle sue condizioni.

Dettagli in [`ATTRIBUZIONI.txt`](ATTRIBUZIONI.txt). I dati sono forniti così come sono, senza
garanzia di completezza o esattezza.

## English

A free, monthly-updated CSV of the municipalities (*comuni*) of the Veneto region of Italy:
postal codes (CAP, including municipalities with several), certified email (PEC), ISTAT and
cadastral codes, province and region. The complete dataset for all of Italy is at
[comunidb.it](https://comunidb.it).
