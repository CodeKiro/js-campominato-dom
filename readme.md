<!-- L'utente clicca su un bottone che genererà una griglia di gioco quadrata. Ogni cella ha un numero progressivo, da 1 a 100. Ci saranno quindi 10 caselle per ognuna delle 10 righe. Quando l'utente clicca su ogni cella, la cella cliccata si colora di azzurro ed emetto un messaggio in console con il numero della cella cliccata.
Bonus
Aggiungere una select accanto al bottone di generazione, che fornisca una scelta tra tre diversi livelli di difficoltà:
con difficoltà 1 => 100 caselle, con un numero compreso tra 1 e 100, divise in 10 caselle per 10 righe;
con difficoltà 2 => 81 caselle, con un numero compreso tra 1 e 81, divise in 9 caselle per 9 righe;
con difficoltà 3 => 49 caselle, con un numero compreso tra 1 e 49, divise in 7 caselle per 7 righe;
Consigli del giorno:
:party_wizard: Scriviamo prima cosa vogliamo fare passo passo in italiano, dividiamo il lavoro in micro problemi.
Ad esempio: Di cosa ho bisogno per generare i numeri?
Proviamo sempre prima con dei console.log() per capire se stiamo ricevendo i dati giusti. Le validazioni e i controlli possiamo farli anche in un secondo momento. -->

\\ L'utente clicca su un bottone, quindi devo creare un event listener da dare al bottone, con il quale verrà generata la tabella del campo minato
    \\ il campo minato viene generato da un ciclo for
        \\ ogni voltaa che l'utente clicca su una cella, si colorerà di azzurro ed emetterà un messaggio in console con il numero della casella cliccata , 

            <!-- Generate Bomb Positions: The function generateUniqueBombs generates 16 unique random numbers between the specified range (1 to 100). The bomb positions are stored in a Set to ensure uniqueness.
Check for Bomb Click: Inside the newGame function, the bombPositions array is checked to see if the clicked cell index is a bomb. If it is, an alert "lose" is shown, and the grid is cleared to end the game.
Game Reset: Clicking the play button starts a new game by calling newGame.
This setup ensures that the game resets each time the play button is clicked, and clicking on a bomb ends the game with an appropriate alert. -->