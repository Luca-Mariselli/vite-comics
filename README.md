MILESTONE 1
Create un nuovo progetto utilizzando Vite e Vue 3
Definite i componenti necessari per strutturare il layout come da screenshot allegato.
Dovrete avere almeno tre componenti: AppHeader, AppMain e AppFooter.
Aiutatevi guardando il codice del live coding di ieri e di oggi e soprattutto controllando cosa cambia tra le varie commit.
MILESTONE 2
Realizzate una struttura a blocchi colorati, come abbiamo fatto in passato per layout lunghi come discord o dropbox.
Quando la struttura è pronta fate in modo di scrivere le voci di menu nel relativo componente, usando i data e un v-for.
Per oggi diamo priorità alla struttura: solo quando è tutto bello solido, passiamo allo style! :warning:
L'obiettivo principale è imparare a muoversi tra i componenti, non realizzare una pagina "bella".
BONUS
Suddividete il main in ulteriori componenti più piccoli, che importerete dal main: effetto matrioska.
Ad esempio, un componente per gestire la fascia azzurra con le icone o altro.


:rock: MILESTONE 1
Create un componente che in base ad un array (in allegato) vada a generare delle card in pagina.
Sarà il macro componente che contiene tutti i fumetti, qualcosa come ComicsList.vue.
Dovrete copiare l'array allegato nel vostro data e iterare con un v-for.
:rock: MILESTONE 2
Ora provate a creare un componente figlio che rappresenti la singola card, del tipo SingleComic.vue.
Fate in modo che accetti un dato in ingresso (usando le props).
Dal componente padre (es. ComicsList) modificate il ciclo in modo che richiami questo nuovo componente e gli passi il fumetto in questione tramite props.
:warning: CONSIGLI
Fate riferimento al codice del live coding per ricordare come passare i dati ai componenti
La funzione per caricare le immagini dinamicamente in mattinata non mi funzionava quando facevo la build perchè va scritta col backtick. Tutto il resto che abbiamo visto resta valido.