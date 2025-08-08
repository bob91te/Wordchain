# Word Chain – Deploy GitHub Pages

## Passi rapidi
1. Crea un **nuovo repository** su GitHub (es. `wordchain`).
2. Scarica questo pacchetto ZIP e **carica tutti i file** nel repo (root, non in una sottocartella).
3. Vai su **Settings → Pages** → *Source*: **Deploy from a branch** → Branch: **main** / folder: **/** → **Save**.
4. Attendi 1–2 minuti. Il sito sarà su: `https://TUO-USERNAME.github.io/wordchain/`.
5. Apri l’URL su iPhone → Condividi → **Aggiungi a Home** (PWA).

## Dizionario
- Il tasto **Pack integrato** carica `italiano_full.json` dal sito e lo salva localmente.
- Puoi anche usare **Carica dizionario…** per caricare un tuo JSON/TXT.

## Sviluppo
- Modifica `index.html` per il gioco.
- `sw.js` e `manifest.webmanifest` abilitano la PWA.
- Le icone sono in `icons/`.
