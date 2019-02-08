## Pływająca małpa

Teraz dodamy małpę, która zaginęła w kosmosie do twojej animacji!

\--- task \--- Zacznij od dodania sprite'a "monkey" z biblioteki.

![Dodanie sprita małpy](images/space-monkey-sprite.png)

\--- / task \---

Kliknij na swój nowy duszek małpy, a następnie kliknij **Kostiumy** , aby móc edytować wygląd małpy.

\--- task \--- Ustawić wypełnienie jako przezroczyste, wybierając czerwoną linię. W przypadku konturu ustaw biały kolor, przesuwając suwak Nasycenie w położenie `0`.

![Zrób biały kolor](images/make-white.png) \--- / task \---

\--- task \--- Kliknij narzędzie **circle** , a następnie użyj go do narysowania białego hełmu wokół głowy małpy.

![Małpi kosmiczny hełm](images/space-monkey-edit.png)

\--- / task \---

\--- task \--- Czy możesz dodać kod do swojej sprite małpy, tak aby obracała się powoli w kółko na zawsze?

\--- wskazówki \--- \--- wskazówka \---

Gdy zielona **flag kliknięciu**, twoja małpa sprite powinien **tura** w okręgu **wiecznie**.

\--- / wskazówka \--- \--- wskazówka \---

Oto potrzebne bloki kodu:

```blocks3
na zawsze
koniec

zakrętu cw (15) stopni

po kliknięciu flagi
```

\--- / wskazówka \--- \--- wskazówka \---

Oto kod, który sprawi, że twoja małpa się zakręci:

![Sprite małpa](images/sprite-monkey.png)

```blocks3
kiedy flaga kliknęła
zawsze
    obrót cw (1) stopni
```

\--- / wskazówka \--- \--- / wskazówki \---

\--- / task \---

Przetestuj i zapisz swój projekt. Będziesz musiał kliknąć czerwony przycisk **zatrzymania** , aby zakończyć tę animację, ponieważ działa ona wiecznie!

![Przetestuj wirującą małpę](images/space-spin-test.png)