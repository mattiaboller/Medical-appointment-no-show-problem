# Medical appointment no-show problem
I pazienti che non si presentano agli appuntamenti programmati dai loro medici causano disguidi in termini di tempo, in
quanto altri avrebbero potuto presentarsi al loro posto, e in termini di spese, per via delle remunerazioni non pervenute a
medici e dottori. Sarebbe pertanto utile riuscire ad identificare i pazienti con alta probabilità di assenza prima che
l’appuntamento abbia luogo.
La domanda di ricerca che ci si è posti, e a cui si è voluto rispondere, riguarda proprio la previsione della probabilità di
no-show dei pazienti, sulla base di dati come: la distanza in giorni che intercorre tra la prenotazione e il giorno effettivo
della visita, l’età, il sesso e altre caratteristiche fisiologiche e sociali. Per ovvia natura, il dataset risulta essere sbilanciato
sulla classe positiva dell’attributo no-show, pertanto si è da subito fatto ricorso a funzioni che migliorassero lo squilibrio,
per poi ricorrere a diversi modelli di classificazione che vengono infine comparati per giungere ad una soluzione ottimale
nel contesto del problema.

