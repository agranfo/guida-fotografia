# Guida di fotografia per la Sony A6600

Guida interattiva in italiano per imparare a fotografare con la **Sony A6600** e l'obiettivo **16-50 mm**, con filtri UV, CPL e ND.

Ogni lezione segue il metodo **Studia → Fai → Ripeti**:

- **Studia**: la teoria in poche righe, con consigli specifici per la A6600
- **Fai**: esercizi pratici da spuntare
- **Ripeti**: varianti e sfide, con contatore delle sessioni di pratica

Lezioni: esposizione, regola dei terzi, simmetria, linee e cornici, luce, filtri.

I progressi vengono salvati nel browser del dispositivo (localStorage). La pagina funziona da smartphone e da PC e non ha bisogno di installazione.

## Come aprirla online (GitHub Pages)

1. Su GitHub crea un nuovo repository pubblico, per esempio `guida-fotografia`.
2. Carica `index.html` e `README.md` (Add file → Upload files → Commit changes).
3. Vai in **Settings → Pages**.
4. In *Build and deployment* scegli **Deploy from a branch**, branch **main**, cartella **/ (root)**, poi **Save**.
5. Dopo 1-2 minuti la guida sarà online su:

   `https://TUO-UTENTE.github.io/guida-fotografia/`

Per aggiornare la guida basta sostituire `index.html` nel repository.

## Con Git da terminale

```bash
git init
git add .
git commit -m "Prima versione della guida"
git branch -M main
git remote add origin https://github.com/TUO-UTENTE/guida-fotografia.git
git push -u origin main
```

Poi attiva GitHub Pages come al punto 3.

## Stampare come PDF

Dal PC apri la pagina, premi `Ctrl+P` e scegli *Salva come PDF*.
