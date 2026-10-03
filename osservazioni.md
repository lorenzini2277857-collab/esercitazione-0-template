# Osservazioni — Esercitazione 0

Gruppo: C9

Componenti (nome, cognome e username GitHub di entrambi): Francesco Lorenzini lorenzini2277857-collab || Riccardo Lella riccardolella

URL del repository condiviso: https://github.com/lorenzini2277857-collab/esercitazione-0-template (entrambi i repository sono stati usati con risultati simili)

Chi ha usato la tastiera nello step 1 e nello step 2: tutti e due

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione: gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello (oppure make)

Comando di esecuzione e risultato osservato: ./hello e si è notato che ha stampato il contenuto scritto (Hello, computational physics!)
 

Che cosa ho capito su sorgente ed eseguibile: che per poter applicare le modifiche della sorgente è necessaria la compilazione prima dell'esecuzione

Output richiesto e comportamento del programma prima della modifica: prima della modifica non veniva stampato nulla, mentre la consegna chiedeva di stampare (Hello, computational physics!)

Esito dopo la modifica e spiegazione della correzione: effettuando una modifica è necessario ricompilare l'eseguibile per poi usare il comando ./hello > output.txt

## Step 1 — Git

Quali file ho incluso nel commit e perché: sono stati aggiunti file di estensione .c o .txt, non eseguibili essendo molto pesanti

Come ho verificato che la versione provata sia presente su GitHub: è stato aperto github e notato se sono presenti i file inseriti nel commit

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone: git pull aggiorna una cartella gia presente, quindi non è richiesto un secondo clone

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato: sono stati passati come argomenti della fuznione una char, un intero e un double che sono stati stampati

Che cosa posso concludere: che a differenza di scanf risulta più comodo inserire le variabili di input

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato: argomento sono stati passati input che rispettassero le ipotesi fatte durante la scrittura del codice e di fatto sono stati stampati sul file .txt

Che cosa ho capito su testo, conversioni e stampa: che è possibile usare > per semplificare l'uscita dei dati creati da un eseguibile, e inserirli direttamente in un .tx, ed è possibile usare le variabili descritte per il seguente esercizio per poter effettuare una sola "esecuzione", si dice esecuzione in batch (termine trovato su google)

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`: ci si aspetta che il secondo restituisca un errore e il primo no

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati: nel primo caso e nel secondo utilizzando atoi non si sono riscontrati errori, ma nel secondo caso è stato salvato uno zero al posto del char

Come un controllo automatico può riconoscere un errore: un modo può essere usare la funzione strtol, che di fatto legge tutti gli elementi di un array modimensionale, e si ferma in prensenza di un carattere, salvando l'indirizzo di memoria dove questo è avvenuto, di fatto è possibile sfruttare questo per accorgersi dell'errore e sfruttare fprintf di stderr per stampare subito l'errore.

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti:

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step:

Come ho verificato che la versione finale sia presente su GitHub:
