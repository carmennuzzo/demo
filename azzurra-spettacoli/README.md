# Azzurra Spettacoli — Sito ufficiale

Sito one-page per **Azzurra Spettacoli**, agenzia di organizzazione e realizzazione di eventi e concerti in esclusiva in Campania e Basilicata.

## Come pubblicarlo su GitHub Pages

1. Crea un nuovo repository su GitHub (es. `azzurra-spettacoli`).
2. Carica **tutto il contenuto di questa cartella** (non la cartella stessa): `index.html`, `assets/`, `gallery/`, `artisti/`.
3. Vai su **Settings → Pages**.
4. In *Source* seleziona il branch `main` e la cartella `/ (root)`, poi salva.
5. Dopo qualche minuto il sito sarà online all'indirizzo `https://<tuo-utente>.github.io/azzurra-spettacoli/`.

## Struttura

```
index.html            → la pagina del sito
assets/logo.png       → logo Azzurra Spettacoli
gallery/              → foto di truck, palchi e allestimenti (sezione "Chi ci ha scelto" e Servizi)
artisti/              → qui vanno le foto degli artisti (vedi sotto)
```

## Foto degli artisti

La sezione **Cast 2026** mostra una card per ogni artista. Per far comparire la foto,
metti l'immagine nella cartella `artisti/` con il nome-file corretto.

L'elenco completo dei nomi-file è in **`artisti/ELENCO-FOTO.txt`**.
Esempi:

- `artisti/tiromancino.jpg`
- `artisti/roberto-vecchioni.jpg`
- `artisti/ron.jpg`

Dove la foto manca, la card mostra automaticamente le iniziali dell'artista: il sito
resta pulito anche senza tutte le immagini.

> Nota: usa solo immagini di cui hai i diritti (le card ufficiali prodotte da Azzurra Spettacoli).

## Contatti / form

Il form nella sezione *Contatti* apre una mail precompilata. L'indirizzo di destinazione
è impostato su `info@azzurraspettacoli.it` dentro `index.html` (funzione `handleSubmit`):
cambialo con l'indirizzo giusto se serve.

## Prossimi eventi

La sezione *Prossimi eventi* è un segnaposto: il calendario vero e proprio verrà aggiunto
in un secondo momento.

---

Sito creato da **Carmen Nuzzo**.
