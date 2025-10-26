# Mój Pierwszy Shopify Theme

To jest mój pierwszy theme na Shopify stworzony lokalnie dla nauki i testowania.

## 🚀 Jak uruchomić lokalne środowisko deweloperskie

### Wymagania
- Shopify CLI (zainstalowany)
- Development Store w Shopify
- Git i GitHub (skonfigurowane)

### Kroki

1. **Zaloguj się do Shopify CLI:**
   ```bash
   shopify auth login
   ```

2. **Uruchom lokalny serwer deweloperski:**
   ```bash
   shopify theme dev
   ```

3. **Otwórz przeglądarkę na:** `http://127.0.0.1:9292`

## 📁 Struktura projektu

```
moj-pierwszy-theme/
├── assets/          # CSS, JS, obrazy
├── blocks/          # Bloki tematyczne
├── config/          # Ustawienia theme
├── layout/          # Szablony layoutów
├── locales/         # Pliki językowe
├── sections/        # Sekcje strony
├── snippets/        # Fragmenty kodu
└── templates/       # Szablony stron
```

## 🛠️ Przydatne komendy

- `shopify theme dev` - Uruchom lokalny serwer
- `shopify theme push` - Wyślij theme do sklepu
- `shopify theme pull` - Pobierz theme ze sklepu
- `shopify theme list` - Lista theme'ów w sklepie

## 📚 Przydatne linki

- [Shopify Theme Development](https://shopify.dev/docs/themes)
- [Liquid Template Language](https://shopify.dev/docs/api/liquid)
- [Shopify CLI Documentation](https://shopify.dev/docs/themes/tools/cli)

## 🎯 Następne kroki

1. Zmodyfikuj pliki w folderze `sections/` aby dostosować wygląd
2. Dodaj własne style CSS w `assets/`
3. Eksperymentuj z różnymi szablonami w `templates/`
4. Testuj zmiany w czasie rzeczywistym używając `shopify theme dev`

---

**Repozytorium GitHub:** https://github.com/konbinipolska-alt/moj-pierwszy-theme