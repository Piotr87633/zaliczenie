# Zasady współpracy - ZOO Online

## Zgłaszanie błędów

Jeśli znajdziesz błąd, utwórz nowe zgłoszenie w sekcji Issues i opisz, co dokładnie nie działa. Dodaj kroki potrzebne do odtworzenia problemu, oczekiwany rezultat oraz aktualny rezultat. Jeśli to możliwe, dołącz zrzut ekranu, logi lub informację o wersji systemu i aplikacji.

## Dodawanie nowych gałęzi

Nowe gałęzie twórz zawsze od aktualnej gałęzi głównej projektu, np. `main` lub `develop`. Nazwa gałęzi powinna krótko opisywać zmianę, np. `feature/login-form` albo `fix/navbar-bug`. Przed rozpoczęciem pracy upewnij się, że Twoja lokalna kopia repozytorium jest aktualna.

## Commitowanie

Commity powinny być małe, logiczne i dotyczyć jednej konkretnej zmiany. Wiadomość commita powinna jasno opisywać, co zostało zmienione, np. `Add login form validation`. Przed wykonaniem commita sprawdź, czy kod działa poprawnie i nie zawiera zbędnych plików.

## Pull requesty

Pull request powinien zawierać krótki opis wprowadzonych zmian oraz informację, jaki problem rozwiązują. Jeśli zmiana jest powiązana z konkretnym zgłoszeniem, dodaj numer issue w opisie, np. `Closes #12`. Przed wysłaniem pull requesta upewnij się, że projekt buduje się poprawnie i przechodzi dostępne testy.

## Styl kodu

Kod powinien być czytelny, spójny i zgodny z przyjętymi zasadami formatowania w projekcie. Stosuj opisowe nazwy zmiennych, funkcji i klas, aby łatwiej było zrozumieć ich przeznaczenie. Przed dodaniem zmian warto uruchomić formatter lub linter, jeśli projekt z nich korzysta.
