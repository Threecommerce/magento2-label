# Changelog

Tutte le modifiche rilevanti a questo modulo sono documentate in questo file.

Il formato è basato su [Keep a Changelog](https://keepachangelog.com/it/1.1.0/)
e questo progetto aderisce al [Semantic Versioning](https://semver.org/lang/it/).

## [1.0.1] - 2026-10-26

### Corretto
- Griglia admin: le colonne Anteprima, Store view e Azioni risultavano vuote (le colonne personalizzate non scrivevano nei dati della griglia).

## [1.0.0] - 2026-10-13

### Added
- Gestione label da admin (3commerce → Label prodotto): griglia con anteprima, azioni massive, form con condizioni, periodo, store view e aspetto.
- Condizioni: SKU selezionati, prodotto nuovo (date native), creati negli ultimi N giorni, in offerta (`{discount}` nel testo), esaurito, valore attributo, tutti i prodotti.
- Priorità e "Nascondi le label a priorità inferiore".
- Inserimento automatico sulle immagini delle liste (per image id) e nella scheda prodotto; view model `Threecommerce\Label\ViewModel\Labels` per i temi che le stampano a mano.
- CSS con variabili, 4 stili, 12 icone SVG, 4 posizioni.
- Traduzione italiana.
