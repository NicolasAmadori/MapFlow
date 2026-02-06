# Soluzione costruita

### La Soluzione Combinata: "Mappa Dinamica Smart-Planner"

Si tratta di un'**interfaccia cartografica centralizzata** che organizza i punti di interesse (POI) su layer temporali e gerarchici, arricchita da "bolle" social geo-localizzate per un'ispirazione immediata. Il sistema integra indicatori visivi di densità temporale e priorità (Must-have vs Nice-to-have), permettendo ricalcoli automatici dell'itinerario in caso di ritardi e filtrando le tappe in base alla tipologia di viaggio.

---

### Connessione ai Bisogni (Needs)

Questa soluzione mira a risolvere simultaneamente tutti i bisogni identificati nel documento:

- **Centralizzazione (Bisogno 1):** Risolve la frammentazione permettendo di accendere/spegnere layer e gestire tutto in un unico luogo.
- **Realismo e Priorità (Bisogni 2 e 4):** Risolve l'ansia da pianificazione errata tramite gli indicatori di densità e la gestione automatica dei "tagli" all'itinerario basata sulla gerarchia visuale.
- **Ispirazione Rapida (Bisogno 3):** Risolve la noia della ricerca tradizionale integrando contenuti video social direttamente sulla mappa.
- **Pertinenza (Bisogno 5):** Risolve il sovraccarico di opzioni tramite filtri adattivi (es. road trip vs relax).

---

### Perché e Come abbiamo selezionato questa soluzione

**Perché:**

Abbiamo scelto di unificare tutto in una "Mappa Dinamica" perché i bisogni degli utenti oscillano tra due poli opposti: il desiderio di **controllo/efficienza** (stime tempi, gerarchie, centralizzazione) e il desiderio di **scoperta/emozione** (contenuti social, mood).

Creare funzionalità separate avrebbe frammentato l'esperienza. Una mappa intelligente è l'unico strumento capace di essere sia "rigoroso" (gestendo tempi e priorità) che "ispirazionale" (mostrando video e suggerimenti) nello stesso contesto visivo.

**Come:**

Abbiamo selezionato le caratteristiche unendo la logica "backend" della pianificazione con l'interfaccia "frontend" dell'esplorazione:

1. **Fondendo la gestione del tempo con la visualizzazione spaziale:** Invece di una lista oraria separata dalla mappa, i POI stessi diventano indicatori di tempo e priorità (tramite colori e dimensioni).
2. **Integrando i social come layer informativo:** Invece di mandare l'utente su Instagram/TikTok, i contenuti vengono portati dentro l'app come metadati del luogo.
3. **Automatizzando la flessibilità:** L'algoritmo che suggerisce cosa tagliare trasforma l'app da semplice "contenitore" a "assistente attivo".
