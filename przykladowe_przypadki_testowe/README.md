Przykładowe przypadki testowe
=============
Przykładowe przypadki testowe dla systemu magazynowo-księgowego, który testowałam w kolejnej fazie jego rozwoju
-------------

| ID  | 1.  |
| ------------ | ------------ |
| **Twórca**  | Katarzyna Janas  |
| **Tytuł** | Wystawienie faktury sprzedażowej do zlecenia  |
| **Cel**  | Weryfikacja możliwości wystawienia faktury sprzedażowej do zlecenia z poprawnymi danymi Wystawcy.  |
| **Warunki początkowe** | - W systemie istnieje aktywny Użytkownik z uprawnieniami do wystawienia faktury sprzedażowej |
|   | - W systemie istnieje zlecenie  |
|   | - Użytkownik jest zalogowany do systemu, znajduje się w menu Zamówienia  |
| **Kroki**  | **Rezultat**  |
|  1. Z menu głównego wybierz Faktury - Faktury sprzedażowe. | 1. Użytkownik został przeniesiony na ekran Faktur sprzedażowych.  |
| 2. Naciśnij strzałkę przy przycisku Wystaw FV. | 2. Otworzyła się lista menu z możliwymi do wystawienia fakturami.  |
| 3. Z listy wybierz FV do zlecenia. | 3. Pojawiło się okno z wystawionymi zleceniami.  |
| 4. Z okna z wystawionymi zleceniami wybierz zlecenie dwukrotnie na nie klikając. | 4. Użytkownik został przeniesiony do ekarnu Faktury VAT wybranego zlecenia. Pola faktury zostały automatycznie uzupełnione na podstawie wybranego zlecenia.  |
| 5. Sprawdź poprawność danych: <br> XYZ Sp. z o.o. <br> 00-000 Warszawa <br> ul. Kowalskiego 5 <br> NIP 000 000 00 00. | 5. Dane Wystawcy są aktualne. |
| 6. Naciśnij przycisk Zapisz. | 6. Faktura została wystawiona. Użytkownik został przeniesiony do ekranu Faktur sprzedażowych. W tabeli faktur sprzedażowych na pierwszej pozycji znajduje się utworzony przed chwilą dokument. |
| **Priorytet** | Wysoki |
| **Wykonanie Manualne/Automatyczne** | Manualne |
| **Czas na wykonanie** | 2 min. |

| ID  | 2.  |
| -------------- | ------------ |
| **Twórca**  | Katarzyna Janas  |
| **Tytuł** | Podgląd faktury sprzedażowej utworzonej przed datą dokonania aktualizacji danych Wystawcy |
| **Cel**  | Weryfikacja prawidłowości danych Wystawcy na fakturze sprzedażowej utworzonej przed datą aktualizacji danych Wystawcy.  |
| **Warunki początkowe** | - W systemie istnieje aktywny Użytkownik z dostępem do ekranu Faktury sprzedażowe |
|   | - W systemie istnieją faktury sprzedażowe utworzone przed datą aktualizacji danych Wystawcy  |
|   | - Użytkownik jest zalogowany do systemu, znajduje się w menu Zamówienia  |
| **Kroki**  | **Rezultat**  |
|  1. Z menu głównego wybierz Faktury - Faktury sprzedażowe. | 1. Użytkownik został przeniesiony na ekran Faktur sprzedażowych.  |
| 2. Przy użyciu filtru 'Data wystawienia do' wyszukaj fakturę utworzoną przed datą aktualizacji danych Wystawcy. | 2. Na ekaranie pojawiła się lista z wyfiltrowanymi fakturami.  |
| 3. Zaznacz jedną ze zwróconych faktur i naciśnij przycisk Pobierz fakturę. | 3. Pojawiło się okno Drukuj fakturę/Wystaw KP. |
| 4. Naciśnij przycisk Zapisz. | 4. Użytkownik został przeniesiony do nowej zakładki z podglądem wydruku faktury. |
| 5. Sprawdź poprawność danych: <br> XYZ Sp. z o.o. <br> 00-000 Warszawa <br> ul. Kowalskiego 5 <br> NIP 000 000 00 00. | 5. Dane Wystawcy są poprawne. |
| **Priorytet** | Wysoki |
| **Wykonanie Manualne/Automatyczne** | Manualne |
| **Czas na wykonanie** | 2 min. |

| ID  | 3.  |
| -------------- | ------------ |
| **Twórca**  | Katarzyna Janas  |
| **Tytuł** | Dodawanie Nowego klienta |
| **Cel**  | Weryfikacja dodawania Nowego klient z listą 'Opiekun klienta' zawierającą tylko aktywnych Użytkowników. |
| **Warunki początkowe** | - W systemie istnieje aktywny Użytkownik z uprawnieniami do dodawania Nowego klienta |
|   | - Użytkownik jest zalogowany do systemu, znajduje się w menu Zamówienia  |
| **Kroki**  | **Rezultat**  |
|  1. Z menu głównego wybierz Klienci.    | 1. Użytkownik został przeniesiony na ekran Klientów. |
| 2. Naciśnij przycisk Dodaj. | 2. Użytkownik został przeniesiony na ekran dodawania nowego klienta. |
| 3. Uzupełnij pola formularza. | 3. Pola formularza zostały uzupełnione. |
| 4. Naciśnij pole Opiekun klienta. | 4. Rozwinęła się lista zawierająca wyłącznie aktywnych Użytkowników, nie posiadających roli Administartor. |
| 5. Wybierz z listy użytkownika - Opiekuna klienta. | 5. W polu Opiekun klienta pojawił się wybrany Użytkownik. |
| 6. Naciśnij przycisk Zapisz. | 6. Nowy klient został dodany. Użytkownik został przeniesiony do ekarnu Klientów. W tabeli klientów na pierwszej pozycji znajduje się dodany przed chwilą Klient. |
| **Priorytet** | Wysoki |
| **Wykonanie Manualne/Automatyczne** | Manualne |
| **Czas na wykonanie** | 2 min. |

| ID  | 4.  |
| -------------- | ------------ |
| **Twórca**  | Katarzyna Janas  |
| **Tytuł** | Filtrowanie dokumentów kasowych wg typu |
| **Cel**  | Weryfikacja filtru Typ na ekranie Kasy. |
| **Warunki początkowe** | - W systemie istnieje aktywny Użytkownik z uprawnieniami do przeglądania dokumentów kasowych |
|   | - W systemie istnieją dokumenty kasowe KP i KW  |
|   | - Użytkownik jest zalogowany do systemu, znajduje się w menu Zamówienia  |
| **Kroki**  | **Rezultat**  |
|  1.  Z menu głównego wybierz Kasa.         | 1. Użytkownik został przeniesiony na ekran Kasy. |
| 2. Naciśnij pole Typ. | 2. Rozwinęła się lista z dostępnymi opcjami KP, KW. |
| 3. Wybierz KP i naciśnij przycisk Szukaj. | 3. W wyświetlonej tabeli znajdują się tylko dokumenty typu KP. |
| **Priorytet** | Niski |
| **Wykonanie Manualne/Automatyczne** | Manualne |
| **Czas na wykonanie** | 0,5 min. |

| ID  | 5.  |
| -------------- | ------------ |
| **Twórca**  | Katarzyna Janas  |
| **Tytuł** | Wydruku raportu z dokumentami kasowymi |
| **Cel**  | Weryfikacja możliwości wydruku raportu zawierającego dokumenty kasowe. |
| **Warunki początkowe** | - W systemie istnieje aktywny Użytkownik z uprawnieniami do przeglądania dokumentów kasowych |
|   | - W systemie istnieją dokumenty kasowe KP i KW  |
|   | - Użytkownik jest zalogowany do systemu, znajduje się w menu Zamówienia  |
| **Kroki**  | **Rezultat**  |
|  1.  Z menu głównego wybierz Kasa.           | 1. Użytkownik został przeniesiony na ekran Kasy. |
| 2. Zawęź zakres dokumentów w filtrach 'Data wystawienia od' i 'Data wystawienia do' i naciśnij przycisk Szukaj. | 2. W wyświetlonej tabeli znajdują się dokumenty kasowe spełniające warunki użytego filtru. |
| 3. Naciśnij przycisk Drukuj raport. | 3. Użytkownik został przeniesiony do nowej zakładki z podglądem wydruku raportu zawierającym wyfiltrowane wcześniej dokumenty kasowe. |
| **Priorytet** | Średni |
| **Wykonanie Manualne/Automatyczne** | Manualne |
| **Czas na wykonanie** | 1 min. |