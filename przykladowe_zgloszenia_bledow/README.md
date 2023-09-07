Przykładowe zgłoszenia błędów
=============
Przykładowe zgłoszenia błędów dla systemu magazynowo-księgowego, który testowałam w kolejnej fazie jego rozwoju
-------------

| ID  | 1.  |
| ------------ | ------------ |
| **TEMAT** | Nie działa filtr Numer KP/KW na ekranie Kasy  |
| **PRIORYTET**  | niski  |
| **POWTARZALNOŚĆ** | za każdym razem |
| **OPIS**  | Filtr Numer KP/KW na ekranie Kasy nie działa dla Użytkownika z uprawnieniami do przeglądania dokumentów kasowych, zalogowanego poprawnie do systemu. |
| **KROKI TESTOWE**  | 1. Po zalogowaniu do systemu przejdź na ekran Kasy.  |
|   | 2. W pole filtru Numer KP/KW wpisz istniejący numer dokumentu kasowego.  |
|  | 3. Naciśnij przycisk Szukaj.  |
|  | 4. Ekran Kasy nie wyświetla żadnego dokumentu. |
| **ŚRODOWISKO** | produkcja |
| **PRINT SCREEN** | ![](https://github.com/kasiajanas/portfolio/blob/main/przykladowe_zgloszenia_bledow/print_screen/blad_nie_dziala_filtr_numer_kp_kw.png) |

| ID  | 2.  |
| ------------ | ------------ |
| **TEMAT** | Wyszukiwarka na pasku głównego menu nie wyszukuje po numerze faktury sprzedażowej  |
| **PRIORYTET**  | niski  |
| **POWTARZALNOŚĆ** | za każdym razem |
| **OPIS**  | Wyszukiwarka na pasku głównego menu nie wyszukuje faktury sprzedażowej po jej numerze dla Użytkownika z uprawnieniami do przeglądania faktur sprzedażowych, zalogowanego poprawnie do systemu. |
| **KROKI TESTOWE**  | 1. Po zalogowaniu do systemu w wyszukiwarkę na pasku głównego menu (prawy górny róg) wpisz numer istniejącej w wystemie faktury sprzedażowej.  |
|   | 2. Naciśnij przycisk Szukaj.  |
|  | 3. Bieżący ekran pozostaje bez zmian.  |
| **ŚRODOWISKO** | produkcja |
| **PRINT SCREEN** | ![](https://github.com/kasiajanas/portfolio/blob/main/przykladowe_zgloszenia_bledow/print_screen/blad_nie_dziala_wyszukiwarka_na_pasku_glownego_menu.png) |