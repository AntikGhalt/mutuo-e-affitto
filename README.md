# Mutuo e affitto

Simulatore in italiano per impostare un mutuo e confrontare due percorsi con le stesse risorse:
**Compra subito** e **Affitta e investe**.

- **01 · Il mutuo**: rata, interessi, sostenibilità rispetto al reddito, costi e imposte dell’acquisto.
- **02 · Comprare o affittare**: patrimonio netto dei due percorsi nel tempo, con scenari di rendimento,
  fase prudente prima degli acquisti, accumulo dell’anticipo e cambio casa facoltativi.

È un’unica pagina HTML statica (`index.html`), senza dipendenze né build. I dati ISTAT (IPAB) e la curva
Eurirs sono incorporati; il tasso medio BCE si aggiorna dall’API pubblica della BCE quando è raggiungibile.

## Usarlo in locale

Apri `index.html` nel browser.

## Pubblicazione

Il sito è pensato per Vercel come progetto statico: nessun comando di build, cartella di output la radice
del repository. Ogni push su `main` aggiorna la produzione.

## Avvertenza

Stime informative con ipotesi modificabili: non sono una consulenza finanziaria, fiscale, notarile o creditizia.
