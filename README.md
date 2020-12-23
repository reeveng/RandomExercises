# Random oefeningen
## Temperaturen - deel 1
### Introductie
In deze oefening moet je "temperaturen analyseren" en degene die het dichtste bij nul is printen op het scherm.
### Regels
Schrijf een programma dat de temperatuur (van een gegeven set aan input data) het dichtst bij 0 print. Indien er 2 nummers zijn die even ver zijn van 0 dan moet degene met een positieve waarde geprint worden (bijvoorbeeld wanneer je 6 en -6 het, beide 6 verwijderd van 0, dan moet je 6 displayen want 6 is positief). 

#### Methode input
Uw programma moet de data lezen van een standaard scanner (system.in) en het resultaat weergeven via de standaard output (system.out).
```java
// Input:
// lijn 1: N, Het aantal temperaturen dat geanalyseerd moet worden
// lijn 2: Een String met de N temperaturen als gehele getallen gaande van -273 tot 5526

// Output
// Toon 0 (nul) als er geen temperaturen gegeven zijn. Anders, toon je de temperatuur het dichst bij 0.

// Beperkingen
// 0 ≤ N < 10000
```

Voorbeeld:
```java
// input            /*-I-*/          Output
/*---------------------------------------*/
5                   /*-I-*/              1
1 -2 -8 4 5         /*-I-*/
```

Gegeven start:
```java
import java.util.*;
import java.io.*;
import java.math.*;

class Solution {

    public static void main(String args[]) {
        Scanner in = new Scanner(System.in);
        int n = in.nextInt(); // het aantal temperaturen dat geanalyseerd moet worden
        for (int i = 0; i < n; i++) {
            int t = in.nextInt(); // een temperatuur (geheel getal) dat zich tussen -273 en 5526 moet bevinden
        }

        // Schrijf uw antwoord door middel van System.out.println()

        System.out.println("result");
    }
}
```

## Temperaturen - deel 2
Bedenk een aantal mogelijke test scenario's (minstens 4 verschillende)
