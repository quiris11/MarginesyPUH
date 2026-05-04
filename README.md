# Dodawanie marginesów do zeskanowanego pliku PDF

PDF przesyłany PUH-em wymaga pustych marginesów 1.5 cm. Zeskanowane pliki nie spełniają tego warunku i są odrzucane. Narzędzie normalizuje orientację, boxy strony i dodaje marginesy.

Narzędzie działa w przeglądarce. **Plik nie jest wysyłany na żaden serwer**.

Operacje:
1) obracanie do pionu ewentualnego poziomego pliku
2) normalizacja obrotu
3) skalowanie × 0.8571
4) Dopasowanie A4
5) MediaBox = TrimBox = \[0 0 595 841\].

Wynik pracy można pobrać na dysk. Oryginalny plik pozostaje nienaruszony.

Narzędzie korzysta z otwartoźródłowej biblioteki [https://pdf-lib.js.org].
