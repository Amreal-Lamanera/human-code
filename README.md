# Scegliere cosa guardare su Netflix

###### Scegliere cosa guardare su Netflix
###### Che barba, che noia, che noia, che barba!
###### Perché ci si mette sempre un’ora a scegliere cosa guardare la sera? Certo è difficile mettere d’accordo i gusti di tutti, poi dipende anche in base al tempo (o al sonno) che abbiamo. Delle volte si pensa di vedere quel bel film che ci hanno consigliato, mentre altre volte si viene risucchiati da quella serie tv che ci tiene incollati allo schermo. Che senso di vuoto quando poi finisce! 


- Controllo quanto tempo ho a disposizione
- SE non ho tempo (meno di 20 minuti) OR ho sonno
    - Rimando Netflix - FINE
- Prendo il telecomando
- Mi siedo
- Accendo la TV e metto netflix

<!-- TODO: Installazione e Login se avanza tempo - Sono solo? -->

- SE sono solo

    <!-- PRIORITA' NELLA MIA TESTA -->
    - SE so cosa guardare
        - SE è presente
            - Controllo durata
            - SE non ho tempo
                - Aggiungo alla "mia lista" netflix
            - ALTRIMENTI inizio a guardarlo FINE

    <!-- LA MIA LISTA NETFLIX -->
    - SE ho film o serie nella mia lista
        - Controllo durata
        - SE non ho tempo
            - Aggiungo alla "mia lista" netflix
        - ALTRIMENTI 
            - inizio a guardarlo FINE

    <!-- CONSIGLI AMICI -->
    - SE ho consigli di amici
        - PER ogni film o serie consigliata
            - SE è presente
                - guardo il trailer
                - SE mi interessa
                    - Controllo durata
                        - SE non ho tempo
                            - Aggiungo alla "mia lista" netflix
                        - ALTRIMENTI 
                            - inizio a guardarlo FINE
                - ALTRIMENTI (NON MI INTERESSA) 
                    - passo al prossimo consiglio
            - ALTRIMENTI (NON PRESENTE) 
                - passo al prossimo consiglio

    <!-- NESSUNA IDEA O CONSIGLIO -->
    - SE ho fra i 20 e i 60 minuti 
        - entro nel catalogo Serie TV
    - ALTRIMENTI SE ho più di 60 minuti & voglio vedere un film
        - entro nel catalogo FILM
        - ALTRIMENTI (ho più 60 minuti & voglio vedere una serie[anche più episodi])
            - entro nel catalogo Serie TV

    - SE ho una categoria preferita
        - PER ogni film/serie controllo
            - SE l'ho già visto & NON voglio rivederlo
                -Passo al prossimo
            - ALTRIMENTI 
                -SE l'ho già visto & voglio rivederlo
                    - PLAY FINE
                - ALTRIMENTI 
                    - SE NON l'ho visto
                        - guardo il trailer
                        - SE mi interessa
                            - PLAY FINE
                        - ALTRIMENTI (NON mi interessa)
                            - ricomincio CICLO (RIGA 60)

    - PER ogni altra categoria
        - PER ogni film/serie controllo
            - SE l'ho già visto & NON voglio rivederlo
                -Passo al prossimo
            - ALTRIMENTI 
                - SE l'ho già visto & voglio rivederlo
                    - PLAY FINE
                - ALTRIMENTI 
                    -SE NON l'ho visto
                    - guardo il trailer
                    - SE mi interessa
                        - PLAY FINE
                    ALTRIMENTI (NON mi interessa)
                        - ricomincio CICLO (RIGA 75)

    - PER x volte provo tasto "SORPRENDIMI"
        -guardo il trailer
        - SE mi interessa
            - PLAY FINE
        - ALTRIMENTI (NON mi interessa)
            - ricomincio CILCO (RIGA 89)

    - CAMBIO CATALOGO STREAMING O FACCIO ALTRO

- ALTRIMENTI
    <!-- PRIORITA' AL GRUPPO -->
    - SE qualcuno propone un film/serie
        - PER OGNI proposta
        - Controllo durata
        - SE non abbiamo tempo
            - SE mi interessa
                - Aggiungo alla "mia lista" netflix
        - ALTRIMENTI si guarda il trailer tutti insieme
        - SE alla maggioranza va bene
            - PLAY FINE
        - ALTRIMENTI ricomincio CICLO (RIGA 101)