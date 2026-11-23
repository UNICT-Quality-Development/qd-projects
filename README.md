# qd-projects

In questa repository troverete nelle [issues](https://github.com/UNICT-Quality-Development/qd-projects/issues) tutti i progetti presenti 

Legenda:   
🤝 = progetto già consegnato   
✅ = progetto già assegnato   
⬜️ = progetto da assegnare   
🟨 = progetto con un solo studente interessato (fatevi avanti!).  
[2] = indica il numero di studenti previsto per il progetto descritto nella issue (ogni gruppo è composto da 2 persone).    
issue chiusa = attestati inviati o progetto abbandonato

--- 

Per chi volesse assegnato uno specifico progetto, commenti la relativa issue soddisfando il numero di partecipanti richiesti dal progetto e scriva un'e-mail all'indirizzo stefano.borzi@unict.it specificando nome, cognome, matricola e username di Github di ciascun componente del gruppo.
Es. se una issue prevede [2] studenti, è necessario trovare un altro partecipante oltre se stesso e citare l'username GitHub di tutti i membri del gruppo interessati al progetto.

Per chi volesse proporre un'idea di progetto, è possibile [scrivere una issue](https://github.com/UNICT-Quality-Development/qd-projects/issues/new) citando il nome utente dei relativi partecipanti, **descrivendo approfonditamente** tutte le funzionalità previste ed un e-mail all'indirizzo stefano.borzi@unict.it specificando nome, cognome, matricola ed username di GitHub di ciascun componente del gruppo.

Si consiglia di proporre una web application: i test E2E si scrivono con Playwright, che automatizza un browser.

--- 

Ogni progetto dovrà essere sviluppato con l'ausilio di GitHub creando una repository, inoltre, ogni modifica dovrà essere apportata all'interno della repository mediante una Pull Request revisionata da almeno un membro del team.

Ogni progetto prevederà **SEMPRE**:
- lo sviluppo di unit test
- code coverage almeno del 90%
- una pipeline presente all'interno del progetto, che applica linter, type checker e formatter (pylint, flake8, mypy, black ed isort, oppure ruff e ty) e fallisce quando la code coverage scende sotto la soglia minima
- l'utilizzo di git ed i [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)
- l'utilizzo di un auto-formatter (es. black o ruff)
- lo sviluppo di test E2E che coprono i flussi principali dell'applicazione, con Playwright (o equivalente), eseguiti nella pipeline
- un `Dockerfile` che costruisce ed esegue il progetto, con un file `.dockerignore` e un `compose.yaml` quando i servizi sono più di uno
- un workflow che consegna qualcosa in automatico, come una release, un'immagine pubblicata su ghcr.io o un deploy su GitHub Pages
- un file `AGENTS.md` con le regole del progetto per il coding agent, utilizzando un workflow moderno (es. Refine-Plan-Act-Consolidate, RPAC)
- un software cross-platform: Linux, macOS e Windows, x86 e ARM, utilizzabile da desktop, tablet e smartphone
- un README chiaro, con le istruzioni per installare ed eseguire il progetto
- codice, commenti, commit e documentazione scritti in inglese
- uno stack che va oltre una singola libreria, ad esempio con un database oppure un'API o un servizio esterno
- i topic GitHub `unict-sqpd` e `unict-sqpd-2026-2027` (entrambi), per mostrare la repository in [questo catalogo](https://unict-quality-development.github.io/git-catalogue/)



Ogni progetto GitHub dovrà avere la seguente impostazione abilitata nella repository

![image](https://user-images.githubusercontent.com/519778/169588498-cfc6f518-b302-41ec-a205-0f76ee43a528.png)

È possibile trovare questa impostazione seguendo il percorso **“Settings -> Branches -> add Rule”** all’interno della propria repository GitHub (sostituire "master" con "main").

⚠️ ATTENZIONE ⚠️  
Non è possibile applicare queste regole per le repository private create mediante free account (account non github-pro).
