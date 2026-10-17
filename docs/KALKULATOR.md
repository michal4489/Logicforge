# Kalkulator z pamięcią RAM

Otwórz **☰ → Przykładowe układy → kalkulator ram 8bit** lub [pobierz projekt](../examples/kalkulator-ram-8bit.lfg).

![Kalkulator z wynikiem 12](../assets/calculator-example.png)

## Dodawanie 7 + 5

1. Kliknij i puść **C**, aby wyzerować sumę.
2. Kliknij i puść **7**.
3. Kliknij i puść **+/=**. Pojawi się 07.
4. Kliknij i puść **5**.
5. Kliknij i puść **+/=**. Wynik to 12.

Klikaj okrągłe przyciski nad podpisami. W wersji 0.14.0 poprawiono obsługę krótkich naciśnięć podczas symulacji. Kalkulator nie wymaga przełączania w pauzę przed każdym działaniem.

| Przycisk | Działanie |
| --- | --- |
| 0–9 | Wybiera pojedynczy składnik. |
| +/= | Dodaje składnik do przechowywanej sumy. |
| C | Kasuje wynik. |

To kalkulator z akumulatorem. Składniki są jednocyfrowe: 1, a potem 2 wybiera **2**, nie liczbę 12. Wynik jest dziesiętny, dwucyfrowy, od 00 do 99. Po 99 następuje zawinięcie, np. 98 + 5 daje 03.

Dwuklik **CALC-8** otwiera wnętrze IC: RAM 8 bit, pełne sumatory, rejestr klawiatury i korekcję BCD. Dwa wyświetlacze cyfr znajdują się na zewnątrz.

## Wynik się nie zmienia?

- Sprawdź wersję aplikacji; poprawka krótkich kliknięć jest w 0.14.0.
- Naciśnij i puść C, potem cyfrę i +/=.
- Klikaj przycisk, nie sam podpis.
- Otwórz świeżą kopię przykładu, jeśli zmieniałeś połączenia.
- Jeżeli problem pozostał, [zgłoś błąd](https://github.com/michal4489/Logicforge/issues/new/choose).
