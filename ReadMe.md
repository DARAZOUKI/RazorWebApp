# Laboration 1.1 - Enkla Webbplatsen med ASP.NET Core (Razor Pages)

## Projektbeskrivning

Detta projekt är en enkel webbplats skapad med **ASP.NET Core Web App (Razor Pages)**. Webbplatsen består av tre undersidor samt en gemensam layout (_Layout.cshtml). Layouten innehåller grundläggande element som navigeringsmeny, inkludering av CSS och JavaScript, samt stöd för responsiv design.

---

## Innehåll och Funktionalitet

### 1. **index(Home)**
- Innehåller valfri information om webbplatsen.

### 2. **Razor**
- Dynamiskt innehåll skapat med Razor-syntax:
  - En lista med kurser skrivs ut med en `foreach`-loop i en "unordered list".
  - Datum och klockslag för besöket skrivs ut.
  - En kontroll (`if`-sats) kontrollerar om det är fredag. 
    - Om ja: "Idag är det fredag!"
    - Annars: "Idag är det inte fredag!"

### 3. **About**
- Information om utvecklaren som skapat webbplatsen.

---

## Layout (_Layout.cshtml)
- Gemensam mall för alla undersidor med:
  - Navigeringsmeny i vänsterkolumnen.
  - Dagens datum i övre högra hörnet (utskrivet med Razor-syntax).
  - Länkar till CSS och JavaScript-filer från **wwwroot**.

---

## Teknologier och Verktyg

- **ASP.NET Core Web App (Razor Pages)**: För att skapa webbsidor.
- **HTML och CSS**: För struktur och design.
- **JavaScript**: För dynamisk funktionalitet.
- **Razor Syntax**: För server-side rendering och dynamiskt innehåll.





