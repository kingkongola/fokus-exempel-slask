# Fokus-demo för Yrkesväljaren 1.2.4

Minimal reproduktion för att testa fokus-länkning med `href="#id"` och `.focus()`.

## Kör

```bash
npm install
npm run dev
```

## Testa

Öppna http://localhost:5173 och:
1. Klicka på länken "Välj yrke är obligatoriskt"
2. Klicka på knappen "Fokusera via JavaScript"

**Förväntat:** Fokus hamnar i input-fältet inuti komponenten.
