# 🇪🇸 ¡Quizpañol!

Prosta aplikacja webowa do nauki gramatyki języka hiszpańskiego. Powstała z myślą o przygotowaniu do sprawdzianów na Politechnice Warszawskiej, ale doskonale sprawdzi się również do ogólnej nauki i powtórek.

🔗 **Link do strony:** [michaell200.github.io/quizpanol](https://michaell200.github.io/quizpanol/)

---

### 📚 Dostępne lekcje
1. **Me gusta & Reflexivos** – czasowniki typu *gustar* i czasowniki zwrotne.
2. **Pretérito Indefinido** – budowa i użycie czasu przeszłego dokonanego prostego.
3. **Números y fechas** – liczby i daty.
4. **Pretérito Perfecto** – budowa czasu przeszłego złożonego i participio.
5. **Pretérito Imperfecto** – budowa i użycie czasu przeszłego niedokonanego.
6. **Futuro Imperfecto** – budowa i użycie czasu przyszłego prostego.
7. **Imperativo** – tryb rozkazujący i jego formy.

Każda lekcja składa się z części teoretycznej i quizu sprawdzającego wiedzę.

### 🗂️ Struktura projektu
```
├── index.html            # strona główna z listą lekcji
├── lessons/               # poszczególne lekcje (teoria + quiz)
└── shared/
    ├── header.js           # renderowanie nagłówka i przełącznika motywu
    ├── theme-init.js        # ustawienie motywu przed renderem strony (anti-FOUC)
    ├── quiz.js              # wspólny silnik quizów używany przez wszystkie lekcje
    └── styles/
        ├── main.css          # agregator importujący pozostałe arkusze
        ├── base.css          # style globalne i zmienne
        ├── chrome.css        # nagłówek, nawigacja, zakładki
        ├── home.css          # strona główna
        ├── theory.css        # sekcja teorii (tabele, opisy)
        └── quiz.css          # sekcja quizu
```

### 🛠️ Technologie
- **Frontend:** HTML5, CSS3, JavaScript (bez frameworków)
- **Deployment:** GitHub Pages
