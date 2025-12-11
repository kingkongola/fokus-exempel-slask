# Fokus-demo för Yrkesväljaren

Minimal reproduktion för att testa fokus-länkning.

## Steg 1: Skapa `.npmrc`

Skapa filen `.npmrc` i denna mapp med innehållet:

```
@taxonomy:registry=https://gitlab.com/api/v4/projects/74569456/packages/npm/
```

## Steg 2: Installera och kör

```bash
npm install
npm run dev
```

## Steg 3: Testa

Öppna http://localhost:5173 och:
1. Klicka på länken "Välj yrke är obligatoriskt"
2. Klicka på knappen "Fokusera via JavaScript"

**Förväntat:** Fokus hamnar i input-fältet inuti komponenten.
# fokus-exempel-slask
