# home-page-for-google
Spersonalizowana strona startowa do organizowania zakładek. Umożliwia organizowanie linków i notatek w tabelach w ramach kart. Funkcje: ciemny/jasny motyw, automatyczne pobieranie tytułów wideo z YouTube, eksport/import danych (JSON), edycja wpisów. Działa bez serwera na LocalStorage — po prostu otwórz plik w Chrome.

## Proste i wygodne narzędzie do organizowania linków i notatek. Działa lokalnie w przeglądarce, bez serwerów i rejestracji.

### Problem: „Szaleństwo kart”
Wszyscy to znamy: otwierasz przeglądarkę, a tam wisi 50 otwartych kart.
- „Ten artykuł przeczytam później”.
- „Ten film muszę obejrzeć wieczorem”.
- „A ten link będzie mi potrzebny do pracy w przyszłym tygodniu”.

Rezultat: przeglądarka działa wolno, pamięć RAM jest zjadana, a znalezienie potrzebnego linku w tym bałaganie jest niemożliwe. Boisz się zamknąć kartę, żeby nie stracić jej na zawsze. *(Tak, wiem o zwykłych zakładkach, ale nie o nie tutaj chodzi)*.

### Rozwiązanie
Ten projekt to **jeden plik HTML**, który zastępuje standardową stronę startową.
Zamiast trzymać otwartą kartę, po prostu kopiujesz link tutaj, dodajesz notatkę i **ze spokojem zamykasz kartę**. Wszystkie Twoje linki są uporządkowane w kategoriach, a przeglądarka działa szybko.

### Możliwości
1. **Organizacja w kartach**: Twórz kategorie (np.: „Praca”, „YouTube”, „Przepisy”, „Do przeczytania”).
2. **Inteligentne dodawanie**: Wklej link do YouTube, a tytuł wideo zostanie pobrany automatycznie.
3. **Prywatność**: Wszystkie dane są przechowywane tylko w Twojej przeglądarce (LocalStorage). Żadnego wysyłania danych na zewnętrzne serwery.
4. **Dostosowanie**: Ciemny i jasny motyw, ustawienia rozmiaru czcionki.
5. **Bezpieczeństwo danych**: Funkcja eksportu i importu wszystkich danych do pliku JSON (wygodne do przenoszenia na inny komputer lub tworzenia kopii zapasowej).
6. **Brak instalacji**: Po prostu pobierz plik i otwórz go w przeglądarce.

### Jak uruchomić
1. Pobierz plik `index_pl.html` z tego repozytorium.
2. Otwórz go w Google Chrome (lub dowolnej innej przeglądarce).
3. *(Zalecane)* Wejdź w ustawienia przeglądarki *(trzy kropki -> Wygląd -> Pokaż przycisk „Strona główna”)* i ustaw ten plik jako **Stronę startową**.

### Ważne: Co musisz wiedzieć
1. **Nie czyść „Danych witryn” bezmyślnie**: Jeśli zdecydujesz się wyczyścić historię przeglądarki i zaznaczysz *"Pliki cookie i inne dane witryn"*, Twoje wpisy zostaną usunięte.
2. **Tryb Incognito**: Jeśli otworzysz plik w trybie Incognito, wpisy tam zrobione znikną natychmiast po zamknięciu okna.
3. **Różne przeglądarki = Różne dane**: Jeśli otworzysz plik w Chrome, a potem w Firefox — zobaczysz pustą stronę w Firefox. Dane są przypisane do konkretnej przeglądarki.

### Jak się zabezpieczyć
W projekcie znajduje się wbudowana funkcja tworzenia kopii zapasowej:
1. Kliknij dużą zębatkę (Ustawienia).
2. Kliknij „Eksportuj wszystko do JSON”.
3. Zapisz plik na swoim komputerze.

*Podobna funkcja dostępna jest również dla każdej karty z osobna.*

Ciesz się porządkiem!
