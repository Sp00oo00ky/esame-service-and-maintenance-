# esame-service-and-maintenance-

# Esame sugli aspetti che riguardano la modifiche ed il testing documentato tramite Jira e Github



## Inizializza il progetto

-Ho creato una repository su GitHub e l’ho clonata in locale con un nome adeguato, poi ho creato un contenitore ed i ticket su Jira.

## Ispeziona il codice 

-Ho creato un nuovo branch "feat/ispezionaCodice"
-Ho cambiato il nome del file in "hello.php"
-Ho ispezionato e testato il codice
-Infine ho oggiornato la repository

## Documenta il progetto

-Ho creato un nuovo branch "feat/documentazione"
-Ho creato questo file README.md, con una breve descrizione del mio lavoro, e del funzionamento del codice.


# Codice su cui sto lavorando
 -----------------------------------------------------

<?php
declare(strict_types=1);

/**
 * Ritorna un saluto personalizzato.
 */

function greet(string $name): string
{
    return "Ciao, {$name}!";
}
$name = $argv[1] ?? "Mondo";
echo greet($name) . PHP_EOL;




# Comandi di esecuzione, ed esempi
 ----------------------------------------------------

// Comando di esecuzione: php hello.php [nome]

// Esempio: php hello.php Mario


# Aggiorna il codice

-Ho creato un nuovo branch "feat/modifiche", per eseguire le modifiche richieste: cambiare il codice in modo che "Ciao" venga stampato in maiuscolo.
Per completare il ticket ho modificato il return in questo modo '' return "CIAO, {$name}!"; ''.





