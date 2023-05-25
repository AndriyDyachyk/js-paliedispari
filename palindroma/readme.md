PROBLEMA:
Chidere all'utente di inserire una parola palindroma, e creare una funzione che identifichi se questa è palindroma o meno.

SOLUZIONE:
1- Richiedere l'inserimento di una parola palindroma da parte dell'utente mediante prompt
2 - Scrivere una funzione che identifichi se la parola è palindroma o meno.
    2.1 - Creare una variabile che prenda il valore del dato inserito dallo user
        2.1.1 - inserire una verifica che permetta di assicurarsi che siano state inserite solo lettere
        2.1.2 - ? se vero, procedere
        2.1.3 - : alert di errore di inserimento ==> richiedere l'inserimento della parola
    2.2 - utilizzare .split() per dividere la parola inserita in lettere
    2.3 - utilizzare .reverse() per capovolgere l'ordine delle lettere
    2.3 - utilizzare .join() per riunire le lettere in un unica stringa come variabile da utilizzare per la verifica
    2.4 - verificare se "parola inserita" == "output della funzione" siano equivalenti
        2.4.1 - ? se vero allora mandare a display la scritta "E' palindroma!"
        2.4.2 - : riportare a schermo "Mi dispiace, non è palindroma."