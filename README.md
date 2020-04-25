# Eserciziario-Basi-Di-Dati

## Esercizio 01
### Biblioteca.drawio
Supponiamo di voler rappresentare i dati relativi ai prestiti che effettua una biblioteca,
ai libri in essa contenuta ed agli scaffali in cui questi sono riposti

## Esercizio 02
### Campionato_calcio.drawio
Supponiamo di voler modellare uno schema E/R delle squadre di calcio che partecipano 
ad un campionato, vogliamo quindi informazioni sulle squadre, sulle partite disputate dalle squadre, informazioni
sui calciatori che giocano in queste squadre, informazioni sugli stadi in cui vengono giocati questi incontri.

## Esercizio 03
### SpettacoloArtisti.drawio
Supponiamo di voler modellare uno schema E/R di una serie di artisti, serie di spettacoli, serie di teatri. Si vogliono conservare 
informazioni su quali artisti rappresentano quali spettacoli in quali teatri.

## Esercizio 04
### Listini.drawio
Si consideri un sistema per la gestione di listini di vendita in valute diverse. 
Un listino è relativo a una zona di vendita, e comprende i prezzi di un insieme di prodotti.
Un prodotto può comparire in più listini; in alcuni listini uno stesso
prodotto può comparire più volte, quotato in valute diverse (ad esempio: lire, dollari e marchi).
A ogni listino è associato uno sconto.
Si disegni un modello concettuale del dominio descritto , utilizzando un formalismo E/R.

## Esercizio 05
### zoo.drawio 🦊
Si vuole automatizzare il sistema  di gestione degli animali in uno zoo.

Ogni esemplare di animale ospitato è identificato
dal suo genere (es. zebra) e da un codice unico all'interno del genere di appartenenza. 

Per ogni esemplare si memorizzano la data di arrivo 
nello zoo, il nome proprio, il sesso, il paese di provenienza e la data di nascita. 

Lo zoo è diviso in aree; in ogni area c'è un insieme case, ognuna destinata un diverso genere di animali. Ogni casa contiene un insieme 
di gabbie, ognuna contenente un solo esemplare.

Ogni casa ha un solo addetto che pulisce ciascuna gabbia in un determinato giorno della settimana. Gli animali sono sottoposti 
periodicamente a controllo veterinario; in un controllo, un veterinario rileva il peso di un esemplare, diagnostica un'eventuale malattia
e prescrive il tipo di dieta da seguire.

Si disegni il modello concettuale del dominio descritto, utilizzando il formalismo E/R

## Esercizio 06
### elenco specifiche-01.drawio
E' dato uno schema relazionale:

- R1 (k1, A1)
- R2 (k2, A2)
- R3 (k1, k2, k3, A3)

Si disegni un possibile schema concettuale E/R corrispondente

## Esercizio 07
### orari_lezioni_uni.drawio
Si intende automatizzare la gestione degli orari delle lezioni in una facoltà universitaria.

La facoltà prevede diversi corsi di laurea (ad esempio, per la facoltà di Ingegneria: corso di laurea
in ingegneria meccanica, ecc.. ), e un certo numero di insegnamenti. 

Ogni insegnamento è contraddistinto da un codice e un nome. 

La maggior parte degli insegnamenti appartiene al piano di studi di più corsi di laurea ( ad esempio 
l'insegnamento C15 Analisi matematica 1 appartiene tanto a ingegneria Elettronica quanto a Ingegneria 
meccanica).

Un dato insegnamento all'interno di un dato corso di Laurea prevede un insieme di lezioni, ciascuna 
svolta in un certo orario e in una certa aula.
 
Gli insegnamenti con molti studenti vengono suddivisi raggruppando alfabeticamente gli studenti;
per un dato insegnamento all'interno di un dato corso di laurea, si possono pertanto avere più docenti
(ad esempio, C15 Analisi Matematica I per Ingenieria Meccanica è suddiviso in due: 
A-K e L-Z, per gli studenti con iniziale del cognome compresa rispettivamente tra A e K e tra L e Z.
Il docente è Rossi per gli A-K, Bianchi per gli L-Z). 

Le lezioni degli insegnamenti con pochi studenti vengono invece unificate per più corsi di Laurea (ad esempio:
le lezioni di "complementi di Matematica" per i Meccanici e i Nucleari sono unificate, e vengono svolte
dal prof. Verdi).

Si disegni il modello concettuale del dominio descritto, utilizzando il formalismo E/R
