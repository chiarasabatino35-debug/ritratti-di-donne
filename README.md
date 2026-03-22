# Nome del progetto: Ritratti di donne
## Descrizione
Il mondo della storia dell'arte è, da sempre, dominato da figure maschili: da Giotto a Picasso, da Botticelli a De Chirico, da Raffaello a Pollock, da Rubens a Van Gogh e altri centinaia di migliaia di nomi. Il ruolo femminile sembra essere rilegato a quello della cosiddetta "musa ispiratrice". Eppure, non poche sono le artiste che hanno saputo distringuersi nel panorama storico-artistico, nonostante le convenzioni sociali che impedivano loro di esprimersi al 100%.
L'obiettivo di questo progetto è mettere in evidenza, oltre al "gender gap", come le restrizioni sociali abbiano influenzato la produzione artistica femminile. E' vero che le donne realizzavano principalmente ritratti e autoritratti? E', forse, anche vero che questa "distinzione sociale" si riflette anche sulla collocazione delle loro opere? E' a queste domande che il progetto "Ritratti di donne" intende dare una risposta.  
## Quali sono i risultati? 
2124 uomini contro 36 donne in un dataframe di 2444 righe non è un caso. I dati analizzati riportano quello che è un sistema di esclusione che va avanti da tempo. Abbiamo avuto la conferma che le donne, per diverse ragioni, erano confinate nel genere del ritratto e dell'autoritratto; mentre la produzione maschile è decisamente più varia. Tuttavia, questa forma di esclusione sembra non coinvolgere il "luogo" nel quale le opere si trovano. Questo dimostra che, nonostante tutto, il valore storico-artistico delle opere realizzate da artiste donne è stato riconosciuto da importanti istituzioni culturali.
## Fonte dei dati
I dati di input utilizzati sono stati presi da un file CSV ("https://raw.githubusercontent.com/dhdmch/2025-2026/refs/heads/main/data/vapod/data.csv") di 229.3+ KB.

| Variabile | Tipo | Definizione | Esempio |
| :--- | :--- | :--- | :--- |
| **id** | int64 | Identificativo univoco dell'opera. | 1, 2, 3 |
| **titoli** | object | Nome dell'opera o del manufatto. | *Portrait of a Lady* |
| **artisti** | object | Genere dell'autore (usato per il filtro). | femmina, maschio |
| **generi** | object | Categoria artistica (es. ritratto). | ritratto, paesaggio |
| **museo** | object | Luogo di conservazione dell'opera. | Museu Nacional |
| **tecnica** | object | Materiali e metodo di realizzazione. | olio su tela |
| **anno** | float64 | Anno di creazione dell'opera. | 1850.0 |
## Metodi e strumenti
Il progetto è stato sviluppato in un ambiente Google Colab utilizzando il linguaggio di programmazione Python. Lo strumento principale utilizzato per la manipolazione, l'analisi e la visualizzazione dei dati è la libreria Pandas.
## Responsabili 
Chiara Sabatino 
## Licenza 
I dati di output sono rilasciati sotto licenza CCO 1.0 Universal ( https://creativecommons.org/publicdomain/zero/1.0/ ).
