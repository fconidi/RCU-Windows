# RCU-Windows — Changelog

## 3.2.0 — 2026-10-16

### Italiano

- Nuova opzione «Includi sottocartelle» nella GUI (salvata nelle preferenze, disattivata di default) e `-Recurse` da console: elabora la cartella scelta e tutto ciò che contiene.
- Ogni cartella inclusa è una raccolta a sé: serie dei suoi file, registro di annullamento proprio, nessun duplicato fra cartelle diverse. L'annullamento ripristina l'ultima operazione di ciascuna cartella.
- Anteprima ed esportazione CSV mostrano i nomi relativi alla cartella scelta; i collegamenti a cartelle non vengono seguiti.
- Include le correzioni della 3.1.1: numeri dell'albo seguiti da virgola (`Serie 1, Titolo`) e regole che eliminano la coda da `Bonelli` in poi.

### English

- New "Include subfolders" option in the GUI (saved in preferences, off by default) and `-Recurse` in the console: process the chosen folder and everything below it.
- Each included folder is its own collection: the series of its own files, its own undo journal, no duplicates across different folders. Undo restores the last operation of each folder.
- Preview and CSV export show names relative to the chosen folder; folder links are not followed.
- Includes the 3.1.1 fixes: issue numbers followed by a comma (`Series 1, Title`) and rules that remove everything from `Bonelli` onward.

## 3.1.0 — 2026-10-08

### Italiano

- Rilevamento automatico della lingua Windows, varianti regionali e fallback inglese; supporto IT/EN/ES/DE/FR.
- Tradotti GUI, editor delle regole e messaggi del motore mostrati nell'interfaccia, inclusi i processi in background.
- Eseguibile autonomo con moduli incorporati; distribuzione con guida in cinque lingue, licenza Go e checksum.
- Aggiornato il launcher per rimuovere le richieste di finestra nascosta, mantenendo la soppressione della console.

### English

- Automatic Windows display-language detection, regional variants and English fallback; IT/EN/ES/DE/FR support.
- Localized GUI, rule editor and displayed engine messages, including background operations.
- Standalone executable with embedded modules; package includes a five-language guide, Go license and checksums.
- Updated the launcher to remove hidden-window requests while retaining console suppression.

## 3.0.0 — 2026-10-07

### Italiano

- GUI ridimensionabile con anteprima, selezione dei file, conflitti espliciti, esportazione CSV e trascinamento cartella.
- Editor guidato di regole letterali o regex, esempi, prova immediata, ordine modificabile e preferenze persistenti.
- Motore condiviso GUI/CLI, pulizia dei metadati e numeri di albo con almeno tre cifre.
- Protezione contro sovrascritture e file cambiati; annullamento con verifica SHA-256 e registri persistenti.

### English

- Resizable GUI with preview, file selection, explicit conflicts, CSV export and folder drag and drop.
- Guided literal/regex rule editor, examples, live testing, reorderable rules and persistent settings.
- Shared GUI/CLI engine, metadata cleanup and issue numbers with at least three digits.
- Protection against overwrites and changed files; undo with SHA-256 verification and persistent history.
