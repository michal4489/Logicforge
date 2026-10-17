<p align="center"><img src="https://github.com/user-attachments/assets/b98d8281-bf2f-4dde-9919-64f077c4824a" alt="LogicForge" width="420"></p>

<h1 align="center">Od pierwszej bramki do własnego procesora.</h1>

<p align="center">Natywny symulator logiki cyfrowej dla Windows.<br>Buduj układy, obserwuj sygnały i zamieniaj pomysły w działającą logikę.</p>

<p align="center"><strong>Windows x64 · Praca offline · Własne IC · RAM · Analiza sygnałów</strong></p>

<p align="center"><a href="https://github.com/michal4489/Logicforge/releases"><strong>Pobieranie i wydania</strong></a> · <a href="docs/START.md">Pierwsze kroki</a> · <a href="examples">Przykłady</a> · <a href="https://github.com/michal4489/Logicforge/issues/new/choose">Zgłoś problem</a></p>

![Ekran startowy LogicForge](https://github.com/user-attachments/assets/3c6f5405-8a03-4956-a6f7-d4e159e4e2ae)

## Zbuduj. Uruchom. Zrozum.

LogicForge pozwala składać układy z bramek, przycisków, zegarów, pamięci i wyświetlaczy. Zacznij od półsumatora, a następnie zamknij większy układ we własnym komponencie IC i użyj go w kolejnym projekcie.

| Możliwość | Co z nią zrobisz |
| --- | --- |
| Edytor układów | Rozmieścisz komponenty i połączysz ich wejścia oraz wyjścia. |
| Symulacja | Sprawdzisz zmiany stanów, zegary i układy sekwencyjne. |
| Własne IC | Zapakujesz obwód w komponent i zajrzysz do jego wnętrza. |
| RAM i wyświetlacze | Zbudujesz zapis, odczyt, liczniki i prosty kalkulator. |
| Analizator sygnałów | Prześledzisz przebiegi i zależności czasowe. |
| Home i tutorial | Wrócisz do ostatnich projektów i poznasz edytor krok po kroku. |

## Zacznij w minutę

1. Otwórz [Releases](https://github.com/michal4489/Logicforge/releases) i wybierz opublikowaną wersję dla Windows x64.
2. Pobierz instalator z sekcji **Assets**. Zawiera środowisko uruchomieniowe; nie wymaga osobnej instalacji .NET.
3. Uruchom LogicForge i wybierz **Tutorial** albo **Projekt powitalny**.
4. Gotowe obwody znajdziesz w **☰ → Przykładowe układy**.

> Pierwsze publiczne wydanie instalatora jest przygotowywane. Dopóki Releases jest puste, plik EXE nie jest dostępny w tym repozytorium. **Code → Download ZIP** pobiera dokumentację i przykłady.

[Instalacja i pierwsze kroki](docs/START.md) · [Pytania i odpowiedzi](docs/FAQ.md)

## Kalkulator z pamięcią

Jedna kość **CALC-8**, klawiatura przyciskowa i dwa wyświetlacze cyfr. W środku działają RAM, pełne sumatory i korekcja BCD.

![Kalkulator z RAM — wynik 12](https://github.com/user-attachments/assets/2dc893d2-b9ad-49c8-a8c2-a81a010d8d4e)

Kliknij kolejno **C → 7 → +/= → 5 → +/=**. Wynik to **12**. Składniki są jednocyfrowe, a suma mieści się w zakresie 00–99 i po jego przekroczeniu zawija się.

[Projekt kalkulatora](examples/kalkulator-ram-8bit.lfg) · [Instrukcja obsługi](docs/KALKULATOR.md)

## Nauka krok po kroku

Tutorial podświetla kolejne elementy i prowadzi przez działanie półsumatora. Wskazane komponenty pozostają interaktywne — zmieniasz wejścia i obserwujesz wynik.

![Tutorial z podświetlonym wejściem A](https://github.com/user-attachments/assets/40e734a0-6214-47aa-a794-f86be45979f7)

## Przykłady do otwarcia

| Projekt | Temat |
| --- | --- |
| [Półsumator](examples/polsumator.lfg) | XOR, AND, suma i przeniesienie. |
| [RAM 8 bit](examples/ram-8bit.lfg) | Zapis i odczyt pamięci. |
| [Kalkulator z RAM](examples/kalkulator-ram-8bit.lfg) | Dodawanie z akumulatorem. |
| [Zegar i przerzutnik](examples/zegar-przerzutnik.lfg) | Układy sekwencyjne. |

Wybierz plik, kliknij **Download raw file**, zapisz jako `.lfg` i otwórz w aplikacji. [Opis przykładów](examples/README.md).

## Pomoc i rozwój

Masz pomysł albo znalazłeś błąd? Otwórz [zgłoszenie](https://github.com/michal4489/Logicforge/issues/new/choose). Podaj wersję aplikacji i kroki odtworzenia problemu. [Zasady zgłoszeń](SUPPORT.md) · [Historia zmian](CHANGELOG.md).

## O repozytorium

To publiczne miejsce dokumentacji, przykładów, zgłoszeń i wydań LogicForge. Kod aplikacji jest rozwijany w prywatnym repozytorium.

LogicForge jest oprogramowaniem własnościowym. Publiczna dostępność repozytorium nie oznacza licencji open source. Warunki korzystania z aplikacji będą podane przy wydaniu. [Informacje o prawach](COPYRIGHT.txt). Zależności zewnętrzne zachowują własne licencje.
