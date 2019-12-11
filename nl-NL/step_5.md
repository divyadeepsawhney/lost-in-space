## Zwevende aap

Nu voeg je aan je animatie een aap toe, die verdwaald is in de ruimte!

\--- task \--- Begin met het toevoegen van de 'Monkey'-sprite uit de bibliotheek.

![Een aap-sprite toevoegen](images/space-monkey-sprite.png)

\--- /task \---

Klik op de nieuwe aap-sprite en daarna op **Uiterlijken** om het uiterlijk van de aap aan te passen.

\--- task \--- Stel een doorzichtige opvulling in door de rode lijn te selecteren. Stel een witte rand in door de Verzadiging naar `0` te schuiven.

![Witte kleur instellen](images/make-white.png) \--- /task \---

\--- task \--- Klik op het **Cirkel** gereedschap en gebruik dit om een witte ruimtehelm rond het hoofd van de aap te tekenen.

![Ruimtehelm voor de aap](images/space-monkey-edit.png)

\--- /task \---

\--- task \--- Kun je code aan de aap-sprite toevoegen, waardoor hij langzaam rond blijft draaien?

\--- hints \--- \--- hint \---

Wanneer de **groene vlag wordt aangeklikt** zou je aap-sprite steeds weer **herhaal**de rondjes moeten blijven **draai**en.

\--- /hint \--- \--- hint \---

Dit zijn de codeblokken die je nodig hebt:

```blocks3
herhaal
einde

draai rechtsom (15) graden 

wanneer op groene vlag wordt geklikt
```

\--- /hint \--- \--- hint \---

Dit is de code om je aap te laten ronddraaien:

![Aap-sprite](images/sprite-monkey.png)

```blocks3
wanneer groene vlag wordt aangeklikt
herhaal 
draai (1) graad rechtsom
```

\--- /hint \--- \--- /hints \---

\--- /task \---

Test en bewaar je project. Druk op de rode **stop**-knop om de animatie te stoppen, anders blijft hij maar doorgaan!

![Test de ronddraaiende aap](images/space-spin-test.png)