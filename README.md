# 📊 Airbnb Data Analysis – Preis- und Stadtteilanalyse 🏠

Dieses Projekt wurde als **persönliches Data-Analytics-Referenzprojekt** erstellt,  
um anhand realer Daten typische Schritte der **Explorativen Datenanalyse (EDA)** durchzuführen und die Ergebnisse verständlich aufzubereiten.

Untersucht werden **Preisstrukturen**, **Unterschiede zwischen Unterkunftstypen** und **Preisunterschiede in verschiedenen Stadtteilen**.

Der Datensatz stammt von **Inside Airbnb** und umfasst detaillierte Informationen zu Unterkünften in einer Großstadt.

---

## 🚀 Ziel des Projekts
- Wie verteilen sich die Preise für Airbnb-Unterkünfte in der Stadt?
- Welche Unterkunftstypen (z. B. Wohnung, Privatzimmer) sind am teuersten?
- In welchen Stadtteilen sind die Unterkünfte besonders teuer oder günstig?

---

## 📂 Projektstruktur
- `data/` – Rohdaten (z. B. `listings.csv`)
- `notebooks/` – Jupyter Notebook mit der Analyse (`airbnb_price_analysis.ipynb`)
- `visuals/` – Diagramme und Plots als PNG-Dateien
- `scripts/` – Python-Skripte (optional)

---

## 📊 Ergebnisse (Auswahl)
---

### 🔸 Preisverteilung 🏷️
Die **meisten Unterkünfte kosten weniger als 200 € pro Nacht**,  
es gibt jedoch **einige Ausreißer im Luxussegment (über 500 € pro Nacht)**.

---

### 🔸 Preise nach Unterkunftstyp 🛏️
- **Ganze Wohnungen sind im Schnitt am teuersten.**
- **Privatzimmer sind günstiger**, während **Gemeinschaftszimmer die günstigste Option** sind.

---

### 🔸 Top 10 teuerste Stadtteile 💎
Die teuersten Viertel befinden sich oft in **zentraler Lage** oder in **touristischen Hotspots**.

![Teuerste Stadtteile](visuals/top_10_teuerste_stadtteile.png)

---

### 🔸 Top 10 günstigste Stadtteile 🏠
Die günstigsten Unterkünfte befinden sich häufig **am Stadtrand** oder in **weniger touristischen Gegenden**.

![Günstigste Stadtteile](visuals/top_10_guenstigste_stadtteile.png)

---

### 🔸 Erkenntnisse aus der Analyse 🧠
- Die **meisten Unterkünfte kosten weniger als 200 € pro Nacht**. Es gibt jedoch **Luxusangebote** mit deutlich höheren Preisen.
- **Ganze Wohnungen** sind im Schnitt am teuersten, gefolgt von **Privatzimmern**. **Gemeinschaftszimmer** sind am günstigsten.
- **Die teuersten Stadtteile** befinden sich oft in **zentralen, touristischen Lagen**.
- **Die günstigsten Stadtteile** liegen eher am **Stadtrand** oder in **weniger gefragten Wohngebieten**.

---

## 📦 Installation & Nutzung
Falls du die Analyse lokal nachverfolgen willst:

```bash
pip install pandas matplotlib seaborn jupyter
jupyter notebook notebooks/airbnb_price_analysis.ipynb
