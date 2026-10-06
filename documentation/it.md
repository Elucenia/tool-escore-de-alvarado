<!-- ELUCENIA technical documentation · escore-de-alvarado · it · no clinical/professional/rights approval -->

# Punteggio di Alvarado

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/escore-de-alvarado)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Migrazione del dolore in fossa iliaca destra

`migra`

### Anoressia (o acetone nelle urine)

`anorex`

### Nausea o vomito

`nausea`

### Dolorabilità in fossa iliaca destra

`dor`

### Dolore al rilascio improvviso (segno di Blumberg)

`desc`

### Temperatura ≥ 37,3 °C

`febre`

### Leucocitosi \> 10.000/mm³

`leuco`

### Deviazione a sinistra (neutrofili \> 75%)

`desvio`

## Edizione del metodo

Alvarado 1986: MANTRELS 8 item, 0–10; versione con deviazione sinistra

## Formula documentata

MANTRELS: Migrazione (1), Anoressia (1), Nausea/vomito (1), T dolorabilità fossa iliaca destra (2), R dolore al rilascio (1), E temperatura elevata (1), Leucocitosi (2), S deviazione sinistra (1). Totale 0 a 10.

## Limiti e popolazione

L’Alvarado 1986 è stato elaborato da 305 pazienti ricoverati con dolore addominale suggestivo di appendicite e otto fattori clinici/di laboratorio. L’abstract originale non valida automaticamente diverse fasce d’età, donne in gravidanza o strategie di dimissione/diagnostica per immagini. Le soglie decisionali e la popolazione della versione utilizzata devono essere verificate separatamente; lo strumento implementa la variante che include la deviazione a sinistra.

## Riferimenti

- [Alvarado A. A practical score for the early diagnosis of acute appendicitis. Ann Emerg Med, 1986.](https://doi.org/10.1016/S0196-0644(86)80993-3)

- [Di Saverio S et al. Diagnosis and treatment of acute appendicitis: 2020 update of the WSES Jerusalem guidelines. World J Emerg Surg, 2020.](https://doi.org/10.1186/s13017-020-00306-3)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Appendicite improbabile (0 a 4)

Considerare altre cause; rivalutare se i sintomi persistono.


### 2

Compatibile con appendicite (5 a 6)

Osservazione e rivalutazione seriale o esame di imaging.


### 3

Appendicite probabile (7 a 8)

Valutazione chirurgica; imaging in base al profilo del paziente.


### 4

Appendicite molto probabile (9 a 10)

Valutazione chirurgica.

