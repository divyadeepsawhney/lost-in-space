## Zwevende aap

Nu zal je aan je animatie een aap toevoegen die verdwaald is in de ruimte!

\--- task \--- Begin met het toevoegen van de 'Monkey'-sprite uit de bibliotheek.

![Adding a monkey sprite](images/space-monkey-sprite.png)

\--- /task \---

Klik op de nieuwe aap-sprite en daarna op **Uiterlijken** om het uiterlijk van de aap aan te passen.

Stel een doorzichtige vulling in door de rode lijn te selecteren. Stel een witte omtrek in door de Verzadiging naar `0` te schuiven.

![Witte kleur instellen](images/make-white.png) \--- /task \---

\--- task \--- Klik op het **Cirkel** gereedschap en teken er een witte ruimtehelm mee rond het hoofd van de aap.

![Monkey space helmet](images/space-monkey-edit.png)

\--- /task \---

\--- task \--- Kan je code toevoegen aan de aap-sprite zodat die de hele tijd ronddraait?

\--- hints \--- \--- hint \---

Wanneer de **groene vlag wordt aangeklikt** zou je aap-sprite **herhaal**delijk in een rondje moeten blijven **draai**en.

\--- /hint \--- \--- hint \---

Dit zijn de codeblokken die je nodig hebt:

```blocks3
herhaal
end

draai (15) graden naar rechts

wanneer groene vlag wordt aangeklikt
```

\--- /hint \--- \--- hint \---

Dit is de code om je aap te laten ronddraaien:

![Aap-sprite](images/sprite-monkey.png)

```blocks3
wanneer groene vlag wordt aangeklikt
herhaal 
  draai (1) graden naar rechts
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---

Test en bewaar je project. Je moet op de rode **stopknop** drukken om de animatie te beëindigen, want die blijft maar doorgaan!

![Test de ronddraaiende aap](images/space-spin-test.png)