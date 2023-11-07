# Esercitazione_4
1) Che cos'è un algoritmo?
Un algoritmo è l'insieme di codice che lo sviluppatore scrive per realizzare una propria idea.
Le singole righe di codice possono essere chiamate "operazioni" mentre l'idea è spesso definitca come un "problema da risolvere".

Per esempio, poniamo che uno sviluppatore sia appassionato di cucina e voglia scrivere un programma che calibri quanti ingredienti utilizzare in base al numero di persone per cui deve servire un
dessert.

In questi casi, il programma da sviluppare è molto basilare ma costituisce di per sé un algoritmo

let people = 3;
let ingredient1 = 300 * people;;
let ingredient2 = 600 * (people /2);
let ingredient3 = 3 + (people / 3);
console.log(ingredient1);
console.log(ingredient2);
console.log(ingredient3);

Il programma interagirà con i valori della ricetta base (300, 600, 3) come specificato dal programmatore e "stampa" sulla riga dei comandi il risultato dei calcoli., in modo da risolvergli il problema di calcolare con precisione di quanto variare le quantità sulla base del numero di persone rappresentate dalla variabile "people".


2) Una variabile è come un contenitore di dati. Può contenere numeri, stringhe e altri tipi di dati per permettere allo sviluppatore di riutilizzarli in seguito.
Supponiamo che uno sviluppatore abbia bisogno di un programma che esegua delle operazioni su un primo numero usando come secondo termine un altro numero da lui definiti.

let operando = 4;
let operatore = 2;

let op1 = operando + operatore;
console.log(op1);
let op2 = operando - operatore;
console.log(op2);
let op3 = operando * operatore;
console.log(op3);
let op4 = operando / operatore;
console.log(op4);

così, grazie alle variabili, i due numeri inseriti dallo sviluppatore verranndo riutilizzati lungo tutto il corso del programma per poi essere trascritti sulla linea di comando per
darne visione al programmatore.

3) Che differenza c'è tra null e undefined?
null indica assenza di valore, undefined assenza di tipo. Pertanto, un null è utilizzabile all'interno delle operazioni tra dati, sebbene non sortisca alcun effetto, mentre undefined non può dar luogo
ad alcuna operazione, quasi come se fosse una variabile inesistente.