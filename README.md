# Platinum — PlayStation Trophy Tracker

Tracker personale dei trofei PlayStation per PS3, PS Vita, PS4 e PS5.

## Pubblicazione su GitHub Pages
Il workflow in `.github/workflows/pages.yml` pubblica automaticamente il sito su ogni push al branch `main`.

1. Apri **Settings → Pages**.
2. In **Build and deployment**, seleziona **GitHub Actions** come Source.
3. Apri **Actions** e attendi il completamento di "Deploy static site".
4. Il sito sarà disponibile su https://filytrav.github.io/PlayStation-Trophy-Tracker/

## Funzioni attuali
- Dashboard con giochi, trofei, platini e completamento medio.
- Libreria PS5, PS4, PS3 e PS Vita.
- Aggiunta, modifica ed eliminazione manuale dei giochi.
- Filtri, roadmap dei giochi in corso e statistiche per piattaforma.
- Persistenza locale nel browser e backup/ripristino JSON.

## Limiti attuali
Questa è una web app statica: i dati restano nel browser e non si sincronizzano automaticamente con PlayStation Network. Non inserire password, NPSSO o token PSN nel sito. La sincronizzazione PSN richiederà un backend separato con gestione sicura delle credenziali e un database.

## Sviluppo
Apri `index.html` direttamente nel browser oppure usa un server statico locale.
