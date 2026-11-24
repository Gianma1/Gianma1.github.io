# Sito "Lezioni di pianoforte a Cervasca"

## 1. Cose da sostituire in `index.html`, `robots.txt` e `sitemap.xml`
Usa "Trova e sostituisci" dell'editor:

| Cerca | Sostituisci con |
|---|---|
| `https://lezioni-piano-cuneo.vercel.app/` | l'indirizzo definitivo del sito |
| `lezionidipianofortecuneo@gmail.com` | l'email di contatto |

Il testo "Chi sono" è segnato con `▼▼▼` dentro `index.html`: incolla lì la descrizione di Superprof.

## 2. Foto
Crea una cartella `img/` accanto a `index.html` e mettici questi file (JPG, lato lungo 1200–1600 px, meglio sotto i 300 KB):

| File | Dove appare | Formato |
|---|---|---|
| `copertina.jpg` | in alto, accanto al titolo | verticale 4:5 |
| `ritratto.jpg` | sezione "Chi sono" | verticale 4:5 |
| `galleria-1.jpg` | galleria, foto grande | verticale o quadrata |
| `galleria-2.jpg` … `galleria-5.jpg` | galleria | orizzontali |
| `condivisione.jpg` | anteprima quando il link è condiviso su WhatsApp/Facebook | 1200×630 |

Finché una foto manca, al suo posto si vede un riquadro rigato (come le corde del pianoforte) con il nome del file.

I file della cartella `fonts/` contengono il carattere del sito (Bodoni Moda, licenza libera SIL OFL): vanno caricati insieme al resto.

## 3. Modulo di contatto (FormSubmit, gratuito)
Il modulo invia le richieste a lezionidipianofortecuneo@gmail.com tramite formsubmit.co, senza account né chiavi.
La prima volta che qualcuno invia il modulo, FormSubmit manda all'indirizzo di contatto un'email "Confirm your email / Activate form":
basta premere il pulsante di attivazione una volta sola. Da quel momento ogni richiesta arriva come email,
e rispondendo si risponde direttamente a chi ha scritto.

## 4. Pubblicazione gratuita su GitHub Pages
1. Su GitHub crea un repository **pubblico** chiamato esattamente `Gianma1.github.io`
   (il sito sarà su `https://lezioni-piano-cuneo.vercel.app/`).
   In alternativa usa un nome qualsiasi, es. `pianoforte`, e il sito sarà su `https://lezioni-piano-cuneo.vercel.app/pianoforte/`
   (in quel caso aggiorna gli indirizzi del punto 1).
2. Carica `index.html`, `robots.txt`, `sitemap.xml` e le cartelle `fonts/` e `img/` ("Add file" → "Upload files").
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, cartella `/ (root)` → Save.
4. Dopo un paio di minuti il sito è online.

## 5. Farsi trovare su Google
1. Vai su https://search.google.com/search-console, aggiungi il sito (proprietà "Prefisso URL")
   e verifica con il file HTML che ti propongono (lo carichi su GitHub come gli altri).
2. In "Sitemap" invia `sitemap.xml`.
3. Mettere il link del sito nel profilo Superprof e sui social aiuta Google a scoprirlo e a fidarsi.
