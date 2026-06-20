# Modifica Controllata

Applica solo la modifica minima approvata nel piano.

Prima di modificare, conferma in una frase:

- task;
- file da toccare;
- prova di controllo;
- cosa resta fuori scope;
- strategia prompt usata: zero-shot o few-shot.

inoltre identifica identifica il componente, hook, stato o funzione effettivamente responsabile del comportamento richiesto.
Evita modifiche speculative in file correlati ma non direttamente coinvolti.

Confini:

- non cambiare layout globale;
- modifica solo i file esplicitamente approvati;
- non cambiare naming, struttura o stile esistente senza necessità;
- non aggiungere nuove feature;
- non fare refactor non richiesti;
- non modificare routing o configurazione;
- fermati se devi toccare file fuori scope.

Dopo la patch:

- mostra il diff;
- spiega cosa e' cambiato;
- indica la prova di controllo.
- riporta solo evidenze brevi: assunzioni principali, criterio usato, verifica proposta.

Livello di confidenza:

Indica una percentuale di confidenza e una frase che giustifichi il valore assegnato.

Se non puoi modificare file direttamente:

- non simulare di averli modificati;
- indicami il blocco di codice da cambiare;
- dimmi dove inserirlo;
- spiega perche' la modifica e' minima;
- indicami come controllarla in VS Code.

Non mostrare chain-of-thought estesa e non aggiungere esempi o alternative fuori scope.
