# Spoki

Gotowa, instalowalna aplikacja webowa dla dzieci. Rozmawia po polsku, angielsku, niderlandzku i suahili. Działa lokalnie bez serwera AI; wypowiedzi nie są wysyłane przez kod aplikacji do własnego backendu.

## Uruchomienie

Mikrofon w przeglądarce wymaga bezpiecznego adresu (`https://`) albo `localhost`.

```bash
python3 -m http.server 8080 --directory .
```

Następnie otwórz `http://localhost:8080`. Najlepsze wsparcie rozpoznawania mowy zapewniają Chrome i Edge. Jeśli przeglądarka nie obsługuje mikrofonu lub danego języka, wszystkie główne zabawy pozostają dostępne przez przyciski.

## Ważne ograniczenie

To jest bezpieczny prototyp regułowy, a nie otwarty chatbot. Nie zapisuje imienia ani historii rozmowy. Dostępność głosów i rozpoznawania suahili zależy od urządzenia i przeglądarki.
