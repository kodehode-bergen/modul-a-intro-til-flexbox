# 🧩 Modul A- intro til Flexbox

Dette prosjektet demonstrerer hvordan man kan bruke **CSS Flexbox** for å lage fleksible, responsive og ryddige layout-strukturer. Her eksperimenteres det med foreldreelementer i hierarki, rekkefølgestyring med `order`, og egenskaper som `flex-wrap`, `flex-direction`, `justify-content`, og `align-items`.

---

## 🎯 Læringsmål

✅ Forstå hvordan `display: flex` påvirker layout  
✅ Bruke `flex-direction` til å styre retning av innhold  
✅ Kontrollere rekkefølge med `order`  
✅ Justere størrelse med `flex-shrink`  
✅ Mestre `flex-wrap` for å håndtere elementer på små skjermer  
✅ Lage komplekse, hierarkiske oppsett med nested Flexbox

---

## 📂 Filoversikt

| Filnavn        | Innhold                          |
|----------------|----------------------------------|
| `index.html`   | HTML-struktur for flex-layout    |
| `style.css`    | CSS med full Flexbox-oppsett     |

---

## 🧱 Strukturelle elementer

### Hovedcontainer: `.grandparent`

```css
display: flex;
flex-direction: column;
justify-content: space-around;
align-items: center;
