CHECKUP AI MOBILE v0.1 – PROTOTYP PWA

Ważne: aplikacja PWA wymaga hostingu HTTPS, aby można ją było dodać do ekranu początkowego i korzystać z kamery/mikrofonu. Sam ZIP nie instaluje aplikacji na iPhonie.

ZAWARTOŚĆ:
- index.html – aplikacja
- manifest.webmanifest – metadane PWA
- sw.js – cache/offline
- icon-192.png i icon-512.png – ikony

FUNKCJE:
- podstawowe informacje dostępne przeglądarce
- sprawdzenie dostępności API baterii (iOS zwykle nie udostępnia kondycji)
- test kolorów i dotyku
- test dostępu do mikrofonu
- test uruchomienia kamery
- test czujnika ruchu, jeśli iOS/ustawienia udostępniają API
- test tonu audio (wymaga subiektywnej oceny odsłuchu)
- raport HTML do wydruku / zapisania jako PDF

INSTALACJA NA IPHONE:
1. Opublikuj zawartość tego folderu w serwisie hostującym statyczne strony z HTTPS (np. GitHub Pages).
2. Otwórz adres HTTPS w Safari na iPhonie.
3. Wybierz Udostępnij -> Dodaj do ekranu początkowego.
4. Uruchom ikonę CheckUp AI z ekranu.

OGRANICZENIA:
- To prototyp webowy, nie natywna aplikacja iOS.
- iOS ogranicza odczyt kondycji baterii, temperatur i szczegółów sprzętu.
- Kamera/mikrofon wymagają zgody i bezpiecznego kontekstu HTTPS.
- Wyniki testów ekranu, głośnika i mikrofonu częściowo wymagają oceny użytkownika.
- Aplikacja nie wysyła danych na serwer; raport jest tworzony lokalnie.
