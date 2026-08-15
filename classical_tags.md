# 📘 Snabbguide: De vanligaste HTML-taggarna

En sammanställning av grundläggande HTML-element för struktur, text, länkar och media.

---

## 🏗️ Sidans grundstruktur

Alla HTML-dokument bygger på denna grundstomme:

| Tagg | Beskrivning |
| :--- | :--- |
| `<!DOCTYPE html>` | Talar om för webbläsaren att dokumentet är skrivet i modern HTML5. |
| `<html>` | Rot-elementet som omsluter allt innehåll på sidan. |
| `<head>` | Innehåller metadata, länk till CSS-stilmallar och sidans titel. Syns inte direkt på sidan. |
| `<title>` | Texten som visas i webbläsarfliken. |
| `<body>` | Allt synligt innehåll (text, bilder, knappar) placeras här. |

---

## 📝 Text & Rubriker

| Tagg | Exempel | Beskrivning |
| :--- | :--- | :--- |
| `<h1>` – `<h6>` | `<h1>Stor rubrik</h1>` | Rubriker i fallande storleksordning (`h1` är störst, `h6` minst). |
| `<p>` | `<p>Detta är en paragraf.</p>` | Vanligt textstycke. Skapar automatiskt luft ovanför och under. |
| `<strong>` | `<strong>Viktig text</strong>` | Gör texten **fetstilt** och markerar semantisk vikt. |
| `<em>` | `<em>Kursiv text</em>` | Gör texten *kursiv* för betoning (*emphasis*). |
| `<br>` | `Rad 1<br>Rad 2` | Skapar ett manuellt radbryt (självstängande tagg). |
| `<hr>` | `<hr>` | Ritar ut en horisontell linje för att dela av sektioner. |

---

## 🔗 Länkar & Media

| Tagg | Exempel | Beskrivning |
| :--- | :--- | :--- |
| `<a>` | `<a href="https://github.com">Länk</a>` | Skapar en klickbar länk. Attributet `href` anger måladressen. |
| `<img />` | `<img src="bild.jpg" alt="Beskrivning">` | Infogar en bild. `src` är sökvägen, `alt` är beskrivande text. |

---

## 📋 Listor

### Punktlista (Osorterad)
```html
<ul>
  <li>Första punkten</li>
  <li>Andra punkten</li>
</ul>