CHECKUP AI iOS v0.6 — PROTOTYP

Instalacja / aktualizacja:
1. Rozpakuj ZIP w aplikacji Pliki na iPhonie.
2. Otwórz repozytorium GitHub: AvantQueTuDis/checkup-ai-mobile.
3. Wybierz Add file -> Upload files.
4. Dodaj WSZYSTKIE pliki z rozpakowanego folderu do katalogu głównego repozytorium.
5. Zatwierdź Commit changes i zaakceptuj zastąpienie istniejących plików.
6. Otwórz https://avantquetudis.github.io/checkup-ai-mobile/ w Safari.
7. Jeśli widzisz starą wersję, zamknij kartę, otwórz stronę ponownie i odśwież. Service worker ma nową nazwę cache v06.

Nowości v0.6:
- odświeżony, ciemny interfejs z kartami i podsumowaniem testów;
- osobne zapisy wyników przedniego i tylnego aparatu;
- mocniejsze, trzytonowe sprawdzenie głośnika (głośność zależy też od przycisków telefonu);
- informacje o sieci, jeśli przeglądarka je udostępnia, oraz orientacyjne opóźnienie do serwera aplikacji;
- nowy, wielostronicowy raport PDF: podsumowanie, wyniki, wskazówki i szczegółowy dziennik;
- brak sztucznej oceny 0–10: raport pokazuje liczbę testów pozytywnych, ograniczeń i problemów.

Ograniczenia:
- iOS/Safari może nie udostępniać poziomu baterii ani typu sieci;
- test sieci nie jest profesjonalnym testem przepustowości. W v0.6 nie deklarujemy prędkości pobierania/wysyłania, jeśli nie ma wiarygodnego pomiaru;
- test aparatu potwierdza uruchomienie strumienia, nie diagnozuje w pełni autofocusu, stabilizacji ani wszystkich fizycznych obiektywów;
- test głośnika odtwarza tony, ale czystość i głośność ocenia użytkownik;
- prototyp nie jest certyfikatem sprawności urządzenia.

Prywatność:
Test mikrofonu i aparatu odbywa się lokalnie w przeglądarce. Nie wysyłamy nagrań ani obrazu do serwera.
