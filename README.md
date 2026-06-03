# ComUnica — documentazione tecnica

Documentazione tecnica sulla composizione di una **Comunicazione Unica d'Impresa** italiana, filtrata allo scope *impresa individuale non agricola*.

📖 **Live**: https://frapasini-fz.github.io/comunica/

## Contenuti

- Struttura della pratica ComUnica (Modello Comunicazione, RI, AdE, INAIL, INPS DM, SUAP)
- Naming conventions dei file (codice pratica + estensioni ufficiali)
- Diagramma decision-tree dei moduli per ente × operazione (Mermaid)
- Tracciato FEDRA per la pratica RI (record-based, coordinate X Y Z)
- Catalogo campi di ogni modulo con regole di compilazione
- Flusso SCIA Contestuale via SSU (callback `suap_send_instance`, CUI uuid)

## Struttura

- `index.html` — documentazione completa (single-page, Mermaid embedded)
- `specs/` — documenti ufficiali consultati (PDF, XSD, txt estratti)

## Fonti

I documenti inclusi in `specs/` sono pubblicazioni ufficiali italiane:

- **Spec ComUnica v3.1** — InfoCamere / Camere di Commercio
- **Allegato A v7.0+** — Decreto MIMIT 12/04/2023, modulistica RI
- **InvioDenunce.xsd** — INAIL
- **PraticaINPS-DM_IAD.xsd** + variazioni — INPS
- **Manuale Operativo SCIA Contestuale** — InfoCamere
- **pratica_suap-2.0.0.xsd** — Impresa in un giorno (DPR 160/2010)

## Pubblicazione

Sito statico — pubblicato via GitHub Pages dalla branch `main`, root.
