<!-- BEGIN DECISION SYSTEM MANAGED INSTRUCTIONS -->
<!-- profile: decision-system-autonomous-completion@1.0.0 -->
<!-- digest: sha256:e94ab22922d5d12abe968442c06bf660552fdd4f916383ecc27295a8b129bd99 -->
<!-- project: ideaforge -->

## Nucleo operativo condiviso

- Prima di agire, riconciliare stato reale del repository, test o CI, ACTIVE_CONTEXT e documentazione canonica.
- Trattare ogni richiesta come mandato a completare il risultato, non soltanto il primo passaggio.
- Proseguire senza conferme ripetute per letture, analisi, modifiche in scope, test, correzioni, retry reversibili, documentazione e Git non distruttivo necessari al risultato.
- Inferire conservativamente i dettagli non materiali e chiedere input soltanto quando la scelta cambia sostanzialmente risultato, costo, rischio o destinatario.
- Terminare soltanto con risultato verificato oppure con un blocker canonico, una motivazione osservabile e una sola azione minima richiesta all'utente.
- Prima della consegna, controllare il risultato dal punto di vista dell'utente, correggere i difetti trovati e rieseguire le verifiche pertinenti.
- Rispettare sempre i confini specifici del progetto, i dati protetti, i divieti espliciti e le autorizzazioni richieste per effetti esterni irreversibili.

Fermarsi per l'utente soltanto in presenza di uno di questi blocker:

- `material_scope_choice_required`
- `irreversible_external_effect_requires_authorization`
- `missing_secret_identity_or_credential`
- `authoritative_sources_conflict`
- `required_capability_unavailable`

<!-- END DECISION SYSTEM MANAGED INSTRUCTIONS -->

# IdeaForge - istruzioni locali

- Consultare `DECISION_SYSTEM.md` e `decision-system.project.json` prima di modificare il progetto.
- Preservare le modifiche preesistenti e limitare il lavoro al risultato richiesto.
- Non inserire credenziali, segreti o dati privati nel repository.
- Non modificare workflow o configurazioni protette attraverso l'aggiornamento automatico delle istruzioni.
- Eseguire i test e i controlli disponibili, correggere le regressioni introdotte e verificare l'output dal punto di vista dell'utente.
- Le evoluzioni automatiche restano `review_required`: possono preparare branch e PR verificati, ma non integrare modifiche applicative senza il gate previsto.
