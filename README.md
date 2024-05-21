# Snake

To klasyczna gra zaimplementowana w Pythonie z użyciem biblioteki Pygame. Gracz kontroluje węża, który porusza się po ekranie, zjadając jedzenie, aby rosnąć. Gra kończy się, gdy wąż zderzy się ze sobą lub z krawędziami ekranu.

## Opis

Projekt składa się z następujących plików:

- `main.py`: Punkt wejścia do gry, który inicjalizuje i uruchamia grę.
- `game.py`: Zawiera klasę `Game`, która obsługuje logikę gry, w tym inicjalizację gry, aktualizację stanu gry, obsługę zdarzeń i renderowanie obiektów gry.
- `game_objects.py`: Zawiera klasy `Snake` i `Food`, które definiują zachowanie i renderowanie węża i jedzenia.
- `config.py`: Zawiera stałe konfiguracyjne dla gry, takie jak wymiary ekranu, rozmiar kafelka, kolory i prędkość węża.

### Funkcje gry

- **Ruch węża**: Węża można kontrolować za pomocą klawiszy strzałek lub klawiszy WSAD.
- **Konsumowanie jedzenia**: Wąż rośnie po zjedzeniu jedzenia, a nowe jedzenie pojawia się w losowych miejscach.
- **Detekcja kolizji**: Gra wykrywa kolizje z krawędziami ekranu i ciałem węża.
- **Wyświetlanie wyniku**: Aktualny wynik (długość węża minus jeden) jest wyświetlany na ekranie.
- **Ekran końcowy**: Po zakończeniu gry wyświetlany jest ekran końcowy z ostatecznym wynikiem i opcją rozpoczęcia nowej gry.

## Sterowanie

- **Klawisze Strzałek / WASD**: Ruch węża.
- **Q**: Wyjście z gry.
- **N**: Rozpocznij nową grę z ekranu końcowego.

## Konfiguracja

Możesz dostosować różne ustawienia gry w pliku `config.py`, takie jak wymiary ekranu, rozmiar kafelka, prędkość węża i kolory.

---

Zachęcamy do dostosowywania gry i jej ulepszania. Wszelkie wkłady są mile widziane! Miłej gry w Snake!
