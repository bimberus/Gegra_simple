# 🌍 Quiz Geograficzny - Prosta Wersja

Lekka, responsywna aplikacja quizowa do nauki geografii w czystym HTML/JavaScript.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

## ✨ Funkcjonalności

- 📚 **40 pytań geograficznych** - szczegółowy trening
- 🎨 **20 ilustracji SVG** - połowa pytań z grafiką
- 🗺️ **Siatka kartograficzna** - współrzędne, południki, równoleżniki
- 🌍 **Ruch obrotowy Ziemi** - dzień i noc, strefy czasowe
- 📍 **Linie geograficzne** - równik, zwrotniki, koła podbiegunowe
- ⏰ **Strefy czasowe** - GMT, linia zmiany daty
- 🎲 **Losowanie pytań** przy każdym uruchomieniu
- 📊 **Progress bar** z postępem quizu
- 💡 **Szczegółowe wyjaśnienia** po każdej odpowiedzi
- 🎯 **System punktacji** z podsumowaniem
- 🔄 **Możliwość ponowienia** testu
- 🌓 **Tryb ciemny** (dark mode)
- 📱 **Responsywny design** (mobile & desktop)
- ⚡ **Błyskawiczne ładowanie** - jeden plik HTML!

## 🚀 Uruchomienie

### Opcja 1: Bezpośrednio w przeglądarce
Otwórz plik `index.html` bezpośrednio w przeglądarce (dwukrotne kliknięcie).

### Opcja 2: Z lokalnym serwerem HTTP

**Python 3:**
```bash
python3 -m http.server 8080
```

**PHP:**
```bash
php -S localhost:8080
```

**Node.js (http-server):**
```bash
npx http-server -p 8080
```

Następnie otwórz w przeglądarce: `http://localhost:8080/`

## 📁 Struktura projektu

```
Gegra_simple/
├── index.html                          # Cała aplikacja (HTML + CSS + JS)
├── src/
│   └── assets/
│       └── images/
│           └── maps/                   # Ilustracje SVG (20 plików)
│               ├── world-map-coordinates-1.svg
│               ├── poland-map-meridian.svg
│               ├── continents-overview.svg
│               ├── equator-line.svg
│               └── ...
└── README.md
```

## 🎓 Kategorie pytań

- 🗺️ **Współrzędne geograficzne** - odczytywanie i określanie położenia
- 🌐 **Siatka kartograficzna** - równoleżniki i południki
- ⏰ **Strefy czasowe** - GMT, różnice czasu między miastami
- 🌍 **Ruch obrotowy Ziemi** - dzień i noc, kierunek obrotu
- 📍 **Główne linie geograficzne** - równik, zwrotniki, koła podbiegunowe
- 🌅 **Konsekwencje ruchu Ziemi** - pory roku, dzień polarny
- 🗓️ **Linia zmiany daty** - międzynarodowa linia 180°
- 🌏 **Kontynenty i oceany** - liczba, położenie, charakterystyka

## 💡 Technologie

- **HTML5** - Struktura aplikacji
- **JavaScript (Vanilla)** - Logika quizu
- **Tailwind CSS** - Style (CDN)
- **SVG** - Ilustracje map

## 📈 Charakterystyka

| Właściwość | Wartość |
|------------|---------|
| Rozmiar HTML | ~35 KB |
| Liczba pytań | 40 |
| Pytania z ilustracjami | 20 (50%) |
| Ilustracje SVG | 27 plików |
| Zależności | 0 (tylko Tailwind z CDN) |
| Build | Nie wymagany |
| Framework | Brak |

## 🎯 Jak dodać nowe pytania

Edytuj tablicę `QUESTIONS` w pliku `index.html`:

```javascript
{
    id: 6,
    text: 'Twoje pytanie?',
    image: 'src/assets/images/maps/twoja-mapa.svg', // opcjonalne
    options: [
        { id: '6a', text: 'Opcja A', correct: false },
        { id: '6b', text: 'Opcja B', correct: true },
        { id: '6c', text: 'Opcja C', correct: false },
        { id: '6d', text: 'Opcja D', correct: false },
    ],
    explanation: 'Wyjaśnienie poprawnej odpowiedzi...',
}
```

## 🆚 Porównanie z wersją Angular

| Cecha | Angular | Prosta wersja |
|-------|---------|---------------|
| Rozmiar bundle | 617 KB | 12 KB |
| Czas ładowania | ~4s build | Natychmiastowy |
| Zależności | 20+ pakietów | 0 |
| Build | Wymagany | Brak |
| Łatwość edycji | Średnia | Bardzo łatwa |
| Stabilność serwera | Problemy | Działa idealnie |

## 📝 Licencja

Projekt edukacyjny - wolne użycie.

## 🤝 Współpraca

Chcesz dodać nowe pytania lub mapy? Pull requesty mile widziane!

---

<div align="center">
Stworzone z ❤️ dla miłośników geografii
</div>
