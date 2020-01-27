# unict-thesis-template
Very simple template for write thesis in LaTeX.

Questo template è pensato per semplificare la stesura della tesi con LaTeX. Il template è pensato per le tesi
dell'Università degli Studi di Catania, ma può essere modificato per qualsiasi altro ateneo italiano.


## Template
![Esempio del pdf generato](https://github.com/Datalux/unict-thesis-template/blob/master/unict.pdf)

# Guida all'utilizzo

## Prerequisiti
Il template fa uso dei seguenti pacchetti:

- `geometry`
- `amsmath`
- `amsfonts`
- `amssymb`
- `graphicx`
- `fancyhdr`
- `float`
- `subscaption`

## Utilizzo
Per utilizzare il template è sufficiente clonare o scaricare la repository.


## Struttura delle cartelle
`unict-thesis-template`

|---- `chapters` : contiene i capitoli della tesi
  
|---- `images` : contiene le immagini 

## Personalizzazione

### Frontespizio
Qui è possibile modificare la pagina iniziale della tesi tramite i segueti comandi:
- `\universita`: cambia il nome dell'universistà, dipartimento e corso di laurea.
- `\studente`: cambia il nome dello studente 
- `\ttitle`: cambia il titolo della tesi
- `\tipo`: cambia il tipo di elaborato (tesi, prova finale, ecc)
- `relatore`: cambia il nome del relatore
- `correlatore`: cambia il nome del correlatore
- `data`: cambia la data della laurea

Per cambiare logo dell'università è sufficiente sovrascrivere l'immagine `images/logo.png` con il logo desiderato.

### Dedica
Per aggiungere una dedica è sufficiente usare il comando `\dedica`

### Indice dei contenuti, tabelle ed immagini
- `\tableofcontents`: aggiunge l'indice dei contenuti
- `\listoftables`: aggiunge l'indice delle tabelle
- `\listoffigures`: aggiunge l'indice delle immagini

### Contenuti
Tutti i contentuti (capitoli, introduzione, ringraziamenti, conclusioni, ecc) andranno messi all'interno della cartella 
`chapters`. Questo non è obbligatorio, ma rende il progetto più pulito. Tutti i contentuti potranno essere caricati all'interno
del file principale tramite i seguenti comandi:
```
\chapter{Titolo del contenuto} (opzionale)
\input{chapters/contenuto}
```

