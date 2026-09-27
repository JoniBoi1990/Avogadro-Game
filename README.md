# 🧭 Projekt Himmelsstürmer – Die Avogadro-Werft
### Interaktives Chemie-Lernspiel für Klasse 10 Gymnasium (Baden-Württemberg)

Ein vollständig selbständiges, interaktives Web-Lernspiel für den Chemieunterricht (Fokus: iPad & GitHub Pages).

---

## 🔬 Didaktischer Aufbau & Level-Progression

1. **Level 1: „Das Geheimnis des Raumes“ ($V \sim n$)**
   - **Lernziel:** Proportionalität zwischen Teilchenanzahl / Stoffmenge und dem Gasvolumen bei konstantem Druck und konstanter Temperatur.
   - **Interaktion:** Schüler pumpen Helium mit einem haptischen Hebel in einen beweglichen Zylinderkolben.

2. **Level 2: „Der Größen-Irrtum“ (Der Kern des Satzes von Avogadro)**
   - **Lernziel:** Auflösen der Fehlvorstellung „größere/schwerere Moleküle brauchen mehr Gasraum“.
   - **Interaktion:** Direkter Vergleich von Helium ($He$, $M = 4\,\text{g/mol}$, winzig) und Schwefelhexafluorid ($SF_6$, $M = 146\,\text{g/mol}$, oktaedrisch riesig).
   - **Erkenntnis:** Beide Gase nehmen bei gleicher Stoffmenge exakt dasselbe Volumen ein, weil der freie Raum zwischen den Teilchen dominiert.

3. **Level 3: „Das Molares-Volumen-Rätsel“ ($V = n \cdot V_m$)**
   - **Lernziel:** Sichere Anwendung der Formeln $V = n \cdot V_m$ und $n = \frac{V}{V_m}$.
   - **Interaktion:** iPad-freundliches On-Screen-NumPad & Stepper zur Betankung von Zeppelin-Kammern mit vorgegebenem Soll-Volumen.

4. **Level 4 (Boss-Level): „Die Rettungs-Mission“ (Synthese & Auftrieb)**
   - **Lernziel:** Verbindung von Avogadro-Gesetz mit Dichte & statischem Auftrieb.
   - **Interaktion:** Schüler wählen das richtige Traggas ($He$ oder $H_2$ vs. $SF_6$ oder $N_2$) und berechnen die exakte Füllmenge. Leichte Gase steigen auf; schwere Gase sinken zu Boden.

5. **Abschluss: „Diplom: Master of Avogadro“**
   - Schüler-Namenseingabe, Sterne-Rang, Datum.
   - Export per **„Als PNG speichern“** oder **„Drucken / PDF“** (optimal für OneNote, GoodNotes, Notability oder Teams).

---

## ⚙️ Physikalische Bedingungen & Molare Volumina (Umschaltbar)

Im oberen Navigationsbalken kann das molare Volumen jederzeit angepasst werden:
- **0 °C (Normbedingungen):** $V_m = 22{,}4\,\text{L/mol}$ ($1013\,\text{hPa}$, Schulbuch-Standard)
- **25 °C (Standardbedingungen / SATP):** $V_m = 24{,}4\,\text{L/mol}$ ($1013\,\text{hPa}$)
- **20 °C (Labor-Raumbedingungen):** $V_m = 24{,}0\,\text{L/mol}$ ($1013\,\text{hPa}$)

---

## 🚀 Bereitstellung auf GitHub Pages (In 1 Minute)

1. Repository auf GitHub erstellen und diese `index.html` (und optional `README.md`) committen & pushen:
   ```bash
   git init
   git add .
   git commit -m "Initial commit Avogadro Werft"
   git branch -M main
   git remote add origin https://github.com/<DEIN-NUTZERNAME>/<REPO-NAME>.git
   git push -u origin main
   ```
2. Auf GitHub im Repository auf **Settings** $\rightarrow$ **Pages** klicken.
3. Unter **Branch** den Branch `main` und Ordner `/ (root)` auswählen und auf **Save** klicken.
4. Nach ca. 30 Sekunden ist das Spiel unter `https://<DEIN-NUTZERNAME>.github.io/<REPO-NAME>/` weltweit auf allen iPads erreichbar!

---

## 📱 iPad-Features

- **Keine störende Bildschirmtastatur:** Alle Eingaben erfolgen über das integrierte Touch-NumPad.
- **Web Audio API:** Realistische Pffft- und Signal-Töne (standardmäßig stummgeschaltet für ruhigen Unterricht).
- **Single-File:** Keine Node-, React- oder NPM-Abhängigkeiten. Funktioniert offline und ohne Cookie-Banner.
