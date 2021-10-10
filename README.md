# human-code
1 attraversare un incrocio sulle strisce (c'è il semaforo?)

VARIABILI
-> STRISCE PEDONALI(boolean) // Ci sono le strisce? Si/No
-> SEMAFORO(boolean) // C'é il semaforo? Si/No
-> VEICOLI(boolean) // Ci sono dei vericoli? Si/No
-> PEDONI(boolean) // Ci sono dei pedoni? Si/No

ALGORITMO
1. Inizio dal marciapiede [INIZIO]
     1a. Ricerca strisce pedonali
        i. Ci sono delle strisce pedonali?
           -TRUE: proseguire 1b
           -FALSE: proseguire di N metri e ripetere 1a
     1b. Raggiunta strisce
        i. Camminare verso le strisce pedonali
        ii. fermarsi davanti alle strisce pedonali
2. C'é il semaforo?
      2a. C'é il semaforo?
        -TRUE:
          i. Il semaforo e' verde?
            -TRUE: Proseguire punto 3a
            -FALSE: Ripetere 2a
        -FALSE:
          ii. Ci sono dei veicoli?
            -TRUE: Ripetere 2a
            -FALSE: Proseguire punto 3a
 3. Attraversare la strada
        3a. Ci sono degli altri pedoni?
            -TRUE: Evitare pedoni
            -FALSE: Proseguire punto 3b
        3b. Camminare sulle strisce
4. Arrivo sull'altro lato della strada [FINE]
    
 
