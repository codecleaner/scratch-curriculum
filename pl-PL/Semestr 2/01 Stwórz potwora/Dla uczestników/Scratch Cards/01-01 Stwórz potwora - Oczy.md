---
title: Karty Scratch - Oczy
level: Poziom 4
language: pl-PL
stylesheet: scratch
embeds: "*.png"
materials: "*.sb2"
...

## Zadania do wykonania { .check}

+ Możesz dodać potworowi oczy, które będą śledzić kursor myszy na całym ekranie. Twój potwór może mieć tyle oczu ile chcesz, nawet osiem, jak pająk! Ponieważ chcemy, żeby oczy naszego potwora ciągle patrzyły na kursor myszki, musimy użyć bloku `zawsze` {.blockyellow}. Po uruchomieniu skryptu **zieloną flagą** oczy `zawsze` {.blockyellow} muszą patrzeć w kierunku myszki i ponownie ustawiać się co ułamek sekundy. 
    ```blocks
        kiedy kliknięto zieloną flagę
            zawsze
                ustaw w stronę [wskaźnik myszy v]
                czekaj (0.2) s
    
        kiedy otrzymam [ruch w prawo v]
            zmień x o (prędkość ruchu)
    
        kiedy otrzymam [ruch w lewo v]
            zmień x o ((prędkość ruchu) * (-1))
    ```

Zauważ, że używamy nadawania wiadomości by ruszać oczami razem z tułowiem i innymi częściami. Co jeszcze mogłyby robić oczy? Jeśli przesuniesz myszkę tak, by znalazłą się pomiędzy oczami potwora, powinny zrobić zeza.
