# Plan strony MUR-BET

## Struktura plików

```
LubiczOgrodzeniaV2/
├── index.html                  # Strona główna (single-page)
├── polityka-prywatnosci.html   # Podstrona - RODO / cookies
├── DANE_FIRMY.md               # Dokumentacja - dane kontaktowe
├── PLAN_STRONY.md              # Ten plik
└── img/
    └── realizacje/
        ├── 01.jpg .. 16.jpg    # Zdjęcia realizacji (16 szt.)
```

## Sekcje strony głównej (index.html)

### 1. Nawigacja (sticky)
- Logo MUR-BET + imię właściciela
- Menu: Start, Oferta, Realizacje, O firmie
- Przycisk CTA z numerem telefonu (667 364 882)
- Responsywne menu mobilne (hamburger)

### 2. Hero Section
- Tło: zdjęcie `realizacje/14.jpg` (brama przesuwna)
- Badge: "Działamy nieprzerwanie od 2006 roku"
- Nagłówek: "Solidne Ogrodzenia i Wyroby Betonowe"
- Podtytuł o zakresie usług
- CTA: "Zadzwoń teraz" + "Zobacz ofertę"

### 3. Zalety firmy (3 boxy)
- Prawie 20 lat doświadczenia
- Produkcja własna
- Kompleksowa usługa

### 4. Oferta (6 boxów)
- Ogrodzenia Panelowe (foto: 10.jpg)
- Ogrodzenia Betonowe (foto: 05.jpg)
- Bramy i Furtki (foto: 06.jpg)
- Podmurówki Betonowe
- Profesjonalny Montaż
- CTA - "Masz inne zlecenie?"

### 5. O firmie
- Opis firmy (rodzinna, od 2006, ul. Owocowa 14)
- Statystyki (2006, 100% polski kapitał)
- Zdjęcie produkcji (11.jpg)

### 6. Realizacje (galeria)
- Grid 4-kolumnowy (desktop) / 3 (tablet) / 2 (mobile)
- 16 zdjęć z lightboxem (strzałki, Esc, licznik)
- Lazy loading obrazków

### 7. Kontakt
- Dane: telefon, email, adres
- Dane rejestrowe (NIP, REGON)
- Embed Google Maps (ul. Owocowa 14, Głogowo)

### 8. Footer
- Logo + claim
- Linki do sekcji
- Link do polityki prywatności
- Copyright

### 9. Cookie Banner
- Pojawia się przy pierwszej wizycie
- Akceptuj / Tylko niezbędne
- Zapis decyzji w localStorage

## Technologie

- HTML5 + Tailwind CSS (CDN)
- Lucide Icons (CDN)
- Google Fonts - Inter
- Google Maps Embed
- Czysty JavaScript (bez frameworka)

## Deploy

- **Docelowo**: hosting OVH (FTP)
- **Testowo**: Netlify Drop (https://euphonious-horse-888960.netlify.app/)

## TODO - przyszłe rozszerzenia

- [ ] Favicon (brak)
- [ ] robots.txt + sitemap.xml (SEO)
- [ ] Formularz kontaktowy (obecnie tylko tel/email)
- [ ] Podstrony z opisem produktów (jeśli będzie potrzeba)
- [ ] Certyfikat SSL (zapewni OVH)
