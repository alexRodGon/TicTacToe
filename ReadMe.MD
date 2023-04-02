Tic Tac Toe
Aquesta aplicació implementa el joc del Tic Tac Toe en Java. El joc es juga entre dos jugadors, un que controla les fitxes X i l'altre que controla les fitxes O. El primer jugador que aconsegueixi tenir 3 fitxes en línia, ja sigui en horitzontal, vertical o diagonal, guanya la partida.

Requisits
Per poder jugar amb aquest projecte, necessitaràs tenir instal·lat a la teva màquina:
-JDK.

Instal·lació
Segueix aquests passos per instal·lar el projecte:
-Descarregar el programa des d'el repositori de GitHub.
-Buscar l'arxiu Java dins de la carpeta src desde la terminal
-Introduir la seguent comanda: java TicTacToe.java

Funcionament
La partida comença amb un tauler de 3x3 cel·les. El programa imprimeix el tauler per pantalla i demana al jugador que indiqui la casella on vol fer el seu moviment. El jugador introdueix la seva posició a través del teclat i el programa actualitza el tauler. Després d'això, és el torn del jugador contrincant, que mou una fitxa dins el tauler de forma aleatòria. Aquesta seqüència es repeteix fins que un jugador guanya o bé es produeix un empat.

Fitxes
El tauler està inicialitzat amb la següent convenció:

Una casella buida és -3.
Una casella amb una fitxa del contrincant és 0.
Una casella amb una fitxa del jugador és 1.
Funcions
La classe TicTacToe conté les següents funcions:

iniciJoc(int[][] taulerJoc)
Inicialitza el tauler de joc a -3, que representa una casella buida.

imprimirTauler(int[][] taulerJoc)
Imprimeix el tauler de joc per pantalla.

crossOrCircle(int i)
Retorna el caràcter que correspon a cada valor de la casella. Retorna '_' per a caselles buides, 'O' per a les caselles amb la fitxa del contrincant i 'X' per a les caselles amb la fitxa del jugador.

tirContrincant(int[][] taulerJoc)
Fa el moviment del jugador contrincant, que consisteix en moure una fitxa a una casella aleatòria.

tirJugador(int[][] taulerJoc)
Demana al jugador la posició on vol fer el seu moviment, a través del teclat, i actualitza el tauler.

main(String[] args)
Funció principal que s'encarrega de gestionar el flux de la partida i cridar les funcions necessàries.