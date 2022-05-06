Harmonogram dla projektu BibliotekaEdit

Temat projektu: Porfel akcji

front

    Okno Logowania
       Pola "login" i "hasło", przyciski: "zaloguj", "nie pamiętam hasła", "rejestracja"
     Okno Rejestracji
        Pola do wypełnienia: "email", "login" i "hasło"
    Okno Wykresu
        Wykres przedstawia dane historyczne, w wybranej przez użytkownika skali, które zaczytuje z tabeli
        Przycisk(i) wyboru skali
        Przyciski wyboru inwestycji. (np 5 różnych)
    Okno mój porfel
          W lewej z góry, stan konta, w prawej z góry, stan wartościowy portfela.
        Tabelka z kolumnami:
          Nazwa 
          Ilość
          Aktualna Cena
          Cena zakupu
          Trend 
       Przyciski: zakup, sprzedaj otwierające okno zakupu (POP-up)
     Okno zakupu:
          Ustalana ilość (wprowadzanie ręcznie +strzałki), przyciski "kup" "sprzedaj" "anuluj" otwierające okno akceptacji.
     Okno ustawień
          Przyciski zmiany hasła, i innych danych użytkownika
     Okno wypłaty/wpłaty
          Przycisk wypłaty środków. 
          Wyświetlenie numeru konta do wpłaty środków - przycisk "kopiuj"
     
    

back

    Baza danych
    
        Tabela Użytkownik:
        login
        haslo
        e-mail
        stan konta
        specjalny numer konta do wpłat (po prostu numer konta)
        
        Tabele Kursy akcji Firma 1...5:
        Dzień
        Cena
        
       
    Operacje na bazie
    
        Generowanie losowych(bądź pobieranie prawdziwych) wartości cen akcji
        Generowanie wykresu w wybranej skali (domyślnie takiej by czas wczytywania był krótki)
        Dodawanie i przechowywanie wartości w bazie danych
        Wczytywanie wartości z bazy.
      
    Bezpieczeństwo
        
        Można zastosować protokoły bezpieczeństwa, wymuszające potwierdzenie operacji przez wirtualny serwer (np handshake)
        Można zastosować algorytm próbujący złamać hasło (siła hasła)
    
        
