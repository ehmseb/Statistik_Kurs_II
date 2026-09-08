# Statistik – Naturwissenschaftliche Forschungswoche

Interaktive E-Learning-Einheit Statistik für die NWW am KSK Kreuzlingen.  
**Roter Faden:** Creme-Bewertungsstudie (Skala 1–9, n = 20, 4 Cremes)

---

## Dateien

| Datei | Beschreibung |
|---|---|
| [`index.html`](index.html) | Interaktiver Statistik-Kurs (5 Module + Quizze) |
| [`theorie.html`](theorie.html) | Begleitdokument mit theoretischem Hintergrund |
| [`Creme-Studie_Statistik.xlsx`](Creme-Studie_Statistik.xlsx) | Excel-Arbeitsmappe zum Ausprobieren (7 Blätter) |

---

## Nutzung

Die HTML-Dateien sind vollständig selbstenthalten (kein Server nötig, keine externen Abhängigkeiten ausser Google Fonts).  
Einfach `index.html` im Browser öffnen – oder via GitHub Pages veröffentlichen.

**GitHub Pages aktivieren:**  
Repository → Settings → Pages → Source: `main` / `root` → Save  
→ Kurs erreichbar unter `https://<username>.github.io/<repo-name>/`

---

## Kurs-Struktur

| Modul | Inhalt |
|---|---|
| 0 · Einstieg | Studienbeschreibung, Rohdaten-Tabelle, Forschungsfrage |
| 1 · Datentypen | Nominal, Ordinal, Metrisch mit Creme-Beispielen |
| 2 · Lageparameter | Modalwert, Median, Mittelwert + interaktiver Rechner |
| 3 · Streumasse | Standardabweichung, Boxplot, IQR |
| 4 · Normalverteilung | Glockenkurve, Schiefe, Shapiro-Wilk |
| 5 · Signifikanz & KI | p-Wert, t-Test, Mann-Whitney, Vertrauensintervall |

Jedes Modul schliesst mit einem Quiz (≥ 80 % für Freischaltung des nächsten).

---

## Excel-Arbeitsmappe (7 Blätter)

1. **Rohdaten** – alle Messwerte (n=20, Cremes 1–4)
2. **Lageparameter** – Modalwert, Median, Mittelwert
3. **Streuung** – SD, Varianz, Quartile, IQR
4. **Normalverteilung** – Häufigkeitstabellen + Diagramme
5. **Signifikanztests** – t-Test und Mann-Whitney U-Test
6. **Vertrauensintervall** – 95%-KI für alle vier Cremes
7. **Meine Daten** – leere Vorlage für eigene Forschungsdaten

---

## Technische Details

- Einzel-Datei HTML (kein Build-Prozess)
- Light / Dark Theme (System + manueller Toggle)
- Schriften: Fraunces (Display), Source Sans 3 (Body), JetBrains Mono (Code/Label) via Google Fonts
- SVG-Visualisierungen, keine externen JS-Libraries
- Druckoptimiert (`@media print`)

---

*KSK Kreuzlingen · Naturwissenschaftliche Forschungswoche · S. Ehm*
