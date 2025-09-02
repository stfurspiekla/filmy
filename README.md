🎬 FILMOWE WYBIERAŃSKO v1.0

📋 Przegląd
FILMOWE WYBIERAŃSKO v1.0 to demokratyczny system wyboru filmów przeznaczony dla dwóch osób, które chcą wspólnie wybrać film do obejrzenia. Łączy elementy strategii, losowości i fair play, aby wyeliminować wieczny problem "co dziś oglądamy?".

✨ Kompletny Zestaw Funkcji

🎭 Główny System Głosowania
- Asymetryczne role: Selektor (Osoba #1) vs Reaktor (Osoba #2)
- System punktowy 1-10: Każda ocena może być użyta tylko raz na osobę
- Sortowanie na żywo: Filmy automatycznie układają się według aktualnych punktów
- Strategiczne ukrywanie: Możliwość ukrycia swojej kolumny głosowania przed drugą osobą
- Randomizacja: Automatyczne mieszanie po ukryciu punktów eliminujące stronniczość
- Blokady bezpieczeństwa: Ukryte punkty nie mogą być odkryte po ukryciu

🏆 Zarządzanie Wynikami i Historią
- Automatyczne wykrywanie zwycięzcy: System oblicza końcowe wyniki i ogłasza zwycięzcę
- Rozstrzyganie remisów: Losowy wybór przy filmach z identycznymi punktami
- Śledzenie historii: Kompletny rejestr obejrzanych filmów z punktami i datami
- Oznaczenia remisów: Ikona 🎲 przy filmach wygranych losowo
- Funkcja cofania: Przywracanie ostatniej sesji głosowania z oryginalnymi punktami
- Czyszczenie historii: Usuwanie pozycji z listy obejrzanych

💾 Zarządzanie Danymi
- Trwałe przechowywanie: Wszystkie dane zapisane w localStorage przeglądarki
- Funkcja eksportu: Pobieranie kompletnej bazy danych jako plik JSON z datą
- Funkcja importu: Przywracanie bazy danych z pliku kopii zapasowej
- Synchronizacja między urządzeniami: Transfer danych między różnymi urządzeniami/przeglądarkami
- Walidacja danych: Automatyczne sprawdzanie integralności importowanych plików

🎮 Interfejs Użytkownika
- Responsywny design: Działa na komputerze, tablecie i telefonie
- Motywy jasny/ciemny: Przełącznik "CIEMNY"/"JASNY" z zapamiętywaniem preferencji
- Polski interfejs: W pełni zlokalizowane doświadczenie użytkownika
- Wizualny feedback: Pogrubiony tekst dla filmów z głosami, kolorowe rankingi
- Inteligentne rozwijane menu: Automatyczne ukrywanie już użytych punktów
- Statystyki na żywo: Rzeczywista liczba filmów w bazie vs obejrzanych

🔧 Funkcje Sterowania
UKRYJ PUNKTY #1/2: Ukrywanie kolumn głosowania (nieodwracalna funkcja bezpieczeństwa)
📊 WYNIKI: Wyświetlanie końcowego rankingu według sumy punktów
🔄 RESTART: Czyszczenie obecnej sesji głosowania (zachowuje filmy i historię)
🏁 ZAKOŃCZ GŁOSOWANIE: Przeniesienie zwycięzcy do historii i reset na następną rundę
↩️ COFNIJ: Cofnięcie ostatniej zakończonej sesji głosowania
📤 EKSPORT BAZY: Pobieranie kopii zapasowej bazy danych
📥 IMPORT BAZY: Przywracanie z pliku kopii zapasowej
❌ USUŃ OSTATNI: Usunięcie ostatniej pozycji z historii

🚀 Co znajduje się w wersji 1.0
Funkcje Pierwszego Wydania
- Kompletna implementacja asymetrycznego systemu głosowania
- Trwałe przechowywanie danych z localStorage
- Funkcjonalność eksportu/importu do zarządzania bazą danych
- Możliwość synchronizacji między urządzeniami
- Kompleksowe śledzenie historii z oznaczeniami remisów
- Responsywny design zoptymalizowany pod wszystkie rozmiary ekranów
- Polski interfejs z kulturową lokalizacją
- Mechaniki strategicznej rozgrywki z ukrytymi informacjami
- Automatyczne systemy randomizacji i rozstrzygania remisów

🛠️ Specyfikacje Techniczne
Wymagania
- Przeglądarka: Nowoczesna przeglądarka z obsługą JavaScript ES6+
- Przechowywanie: API localStorage (pojemność około 5-10MB)
- Używane API: Blob API (eksport), FileReader API (import)
- Responsywność: CSS Grid i Flexbox do layoutu
- Kompatybilność: Chrome 60+, Firefox 55+, Safari 12+, Edge 79+
Formaty Plików
- Format eksportu: JSON z rozszerzeniem .json
Wzorzec nazw plików: filmowe-wybieransko-backup-YYYY-MM-DD.json
Kodowanie znaków: UTF-8
Walidacja danych: Walidacja schematu JSON przy imporcie

Wydajność
- Czas ładowania: < 2 sekundy przy przeciętnym połączeniu
- Zużycie przestrzeni: ~50KB dla 100 filmów z pełną historią
- Użycie pamięci: < 10MB sterty JavaScript podczas normalnej pracy
- Możliwość offline: Pełna funkcjonalność bez połączenia internetowego

📋 Instrukcja Użytkowania
Pierwsze Kroki
- Dodaj filmy: Użyj sekcji "DODAJ NOWY FILM" aby zbudować bazę danych
- Opcjonalna kopia zapasowa: Kliknij "📤 EKSPORT BAZY" aby zapisać obecny stan
- Rozpocznij głosowanie: Osoba #1 przypisuje punkty 1-10 wybranym filmom
- Ukryj punkty: Kliknij "UKRYJ PUNKTY #1" po zakończeniu (nieodwracalne)
- Głosowanie Osoby #2: Tylko na filmy wybrane przez Osobę #1
- Sprawdź wyniki: Kliknij "📊 WYNIKI" aby zobaczyć końcowy ranking
- Zakończ rundę: Kliknij "🏁 ZAKOŃCZ GŁOSOWANIE" aby przenieść zwycięzcę do historii

Wskazówki Strategiczne
- Dla Selektorów: Wybierz różnorodne filmy vs skup się na ulubionych
- Dla Reaktorów: Spróbuj odgadnąć preferencje przeciwnika vs głosuj według własnego gustu
- Pamiętaj: Ukryte informacje tworzą strategiczną głębię

Zarządzanie Danymi
- Regularne kopie zapasowe: Eksportuj przed większymi sesjami głosowania
- Między urządzeniami: Eksportuj z komputera, importuj na telefonie dla kontynuacji głosowania
- Zachowanie historii: Eksportowane pliki zawierają kompletną historię głosowań

⚠️ Znane Ograniczenia
- Przechowywanie w Przeglądarce
- Dane powiązane z konkretną przeglądarką na konkretnym urządzeniu
- Czyszczenie danych przeglądarki usunie wszystkie filmy i historię
- Brak automatycznej synchronizacji w chmurze (wymagany ręczny eksport/import)

Ograniczenia Głosowania
- Maksymalnie 10 filmów może otrzymać punkty od jednej osoby na sesję
- Ukryte punkty nie mogą być odkryte po ukryciu
- Operacja importu całkowicie zastępuje istniejące dane
- Kompatybilność z Przeglądarkami
- Wymaga włączonego JavaScript
- localStorage musi być dostępny (niedostępny w trybie prywatnym w niektórych przeglądarkach)
- Pobieranie/wysyłanie plików wymaga nowoczesnych API przeglądarki

🔒 Bezpieczeństwo i Prywatność

Przechowywanie Danych
- Wszystkie dane przechowywane lokalnie w przeglądarce
- Brak zewnętrznych serwerów lub przechowywania w chmurze
- Nie zbieramy ani nie przesyłamy informacji osobowych
- Pliki eksportu zawierają tylko tytuły filmów, linki i punkty

Funkcje Prywatności
- Ukrywanie punktów zapobiega wpływaniu na głosy między graczami
- Brak implementacji śledzenia lub analityki
- Całkowicie offline działanie po początkowym załadowaniu strony

📱 Obsługa Platform

Komputer
✅ Windows 10/11 (Chrome, Firefox, Edge)
✅ macOS (Chrome, Firefox, Safari)
✅ Linux (Chrome, Firefox)
Telefon
✅ iOS 12+ Safari
✅ Android 7+ Chrome
✅ Responsywny design na telefony
Tablet
✅ iPad (Safari)
✅ Tablety Android (Chrome)
✅ Interfejs zoptymalizowany pod dotyk

🎯 Grupa Docelowa

Główni Użytkownicy
- Pary szukające demokratycznej metody wyboru filmu
- Znajomi chcący wyeliminować paraliż decyzyjny
- Kluby filmowe potrzebujące sprawiedliwego systemu głosowania

🔄 Przyszły Rozwój
Potencjalne Ulepszenia
- Opcje synchronizacji w chmurze
- Wersje aplikacji mobilnych
- Głosowanie grupowe (3+ osób)
- Integracja z rekomendacjami filmowymi
- Zaawansowane statystyki i analityka

Wkład Społeczności
- Zgłoszenia błędów i propozycje funkcji mile widziane
- Wkład w kod przyjmowany przez pull requesty
- Pomoc w tłumaczeniu na dodatkowe języki

Zachęcamy do opinii o doświadczeniu użytkownika

📞 Wsparcie
Zgłaszanie Błędów
- Sprawdź konsolę przeglądarki pod kątem błędów JavaScript
- Zweryfikuj czy localStorage jest włączony i dostępny
- Przetestuj w różnych przeglądarkach aby wyizolować problemy specyficzne dla przeglądarki

Typowe Rozwiązania
- Eksport nie działa: Sprawdź czy przeglądarka nie blokuje pobierania, spróbuj innej przeglądarki
- Import się nie udaje: Zweryfikuj format i poprawność pliku JSON
- Dane utracone: Sprawdź czy dane przeglądarki zostały wyczyszczone, przywróć z kopii zapasowej jeśli dostępna

Stworzone z pasją do demokratycznego podejmowania decyzji i miłością do kina. Zaprojektowane aby przekształcić frustrujące "co powinniśmy oglądać?" w angażujące strategiczne doświadczenie.

- Open Source

Wydane na licencji MIT - wolne do użytkowania, modyfikowania i rozpowszechniania.

🍿 Miłych wieczorów filmowych z demokratycznym podejmowaniem decyzji! 🎬

W przypadku pytań, sugestii lub wkładu, odwiedź repozytorium projektu.

