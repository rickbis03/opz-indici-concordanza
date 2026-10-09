# La mappa degli accordi — versione interattiva

Le quattro griglie e i quattro indici di concordanza del progetto
*Orizzonti Politici*, in una pagina sola e senza dipendenze: si apre,
si passa il puntatore sulle celle e ogni posizione porta alla sua fonte.

- **Dati al 9 ottobre 2026**
- Campo Largo 82,4% · Centro-sinistra 63,9% · Centro-destra 63,7% · Coalizione 59,6%
- Sito: https://rickbis03.github.io/opz-indici-concordanza/
- Articolo: _non ancora pubblicato: manca `PERMALINK_ARTICOLO` in `build_embedded.py`_
- Metodo e fonti: [`NOTA_METODOLOGICA.md`](NOTA_METODOLOGICA.md)

## Cosa c'è in questo repository

| file | che cos'è |
|---|---|
| `index.html` | la pagina interattiva: le due griglie delle posizioni, le due matrici di concordanza, il pannello delle fonti, la navigazione da tastiera |
| `NOTA_METODOLOGICA.md` | come sono state scelte le fonti, su quale arco temporale, che cosa significa ogni punteggio |

`.nojekyll` disattiva l'elaborazione del sito: serve perché il file venga servito
esattamente come è scritto.

## Una fotografia, non una fonte

I valori qui dentro sono quelli del **9 ottobre 2026**. Se un giorno l'articolo è stato
pubblicato con dati più recenti, **l'articolo fa fede**, non questa pagina. Il
pannello delle fonti mostra la data accanto a ogni posizione proprio per rendere
verificabile quale fotografia si sta guardando.

Nessun file di questo repository si modifica a mano: vengono tutti prodotti da
`build_embedded.py` nella cartella di lavoro del progetto. I punteggi non si
correggono qui, si correggono nel database e poi si rigenera tutto.
