# Brand Guardian Lite

Prototipo di controllo qualità per testi di marketing: assegna un punteggio di coerenza col brand da 0 a 100 e segnala i segnali tipici dell'"AI slop" (frasi fatte, parole vietate, testo generico senza dati concreti). La decisione finale resta a una persona, con i pulsanti Approva / Rimanda.

**Demo live:** https://tahabahousse.github.io/brand-guardian-lite/

## Cosa controlla
- Frasi fatte del marketing italiano ("nel cuore di", "esperienza indimenticabile", ...)
- Parole vietate e parole chiave obbligatorie definite dal brand
- Lunghezza massima, punti esclamativi multipli, maiuscole urlate
- Presenza di almeno un dato concreto (prezzo, data, quantità)

Ogni penalità è spiegata, e le parti critiche sono evidenziate nel testo.

## Come funziona
Pagina HTML unica, JavaScript puro, nessuna dipendenza. Tutto gira nel browser: nessun testo viene inviato a server esterni.

## Prossimi passi
- Estrarre le regole in automatico dal brand book con un modello linguistico (Gemini o Claude)
- Proporre una riscrittura che corregge solo le regole violate
- Controllo immagini: confronto tra la foto reale del prodotto e l'immagine generata

## Nota
Progetto personale di Taha Bahousse, realizzato con il supporto di strumenti di AI.
