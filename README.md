Consegna:
Scrivi un programma che stampi i numeri da 1 a 100,
ma per i multipli di 3 stampi “Fizz” al posto del numero e per i multipli di 5 stampi Buzz.
Per i numeri che sono sia multipli di 3 che di 5 stampi FizzBuzz.
Prima di partire a scrivere codice poniamoci qualche domanda:
Come faccio a sapere se un numero è divisibile per?
Abbiamo visto qualcosa di particolare che possiamo usare?
Consigli del giorno:
1. scriviamo sempre prima dei commenti in italiano per capire cosa vogliamo fare
2. proviamo ad immaginare le operazioni che vogliamo far svolgere al nostro programma così come lo faremmo "a mano"



Risoluzione

Racolta logica:
- [ ] Creare un ciclo for dove "i" avrà valore 1 e si ripeterà fino ad essere pari a 100 quindi <= 100 e dire di stampare "i"
- [ ] Creare condizione con if dove se i è divisibile per 3 allora stampiamo "Fizz"
- [ ] Creare condizione con if dove se i è divisibile per 5 allora stampiamo "Buzz"
- [ ] Creare condizione con if dove se i è divisibile per 3 and 5 allora stampiamo FizzBuzz.

Bug riscontrati: 
-Se creamo delle condizioni da cui ci aspettiamo solo valori "true" allora per il numero che avrà entrambe le condizioni "true" allora stamperà sia "Fizz" (perchè è divisibile per 3) sia Buzz (perchè è divisibile per 5) sia "FizzBuzz" (perchè soddisfa tutte le condizioni). Quindi non bisogna solo dire al numero che è divisibile per 3 ma anche che non sia divisibile per 5 e viceversa in modo da poter avere anche una condizione "false" che ci ritorna un valore diverso.
-Per poter stampare i, infatti, gli abbiamo dato una condizione negativa, cioè che non deve essere divisibile nè per 3 nè per 5. 


