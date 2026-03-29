# 🎨 Project: Urban Art Logistics UI (v5.1)
**Category:** Frontend Development / UX Design Study  
**Location:** Münster, Germany (Local Grid)

---

## 📌 Projekt-Übersicht
Dieses Repository ist ein funktionaler Prototyp für eine **Logistik-Schnittstelle**, die speziell für urbane Künstlerkollektive entwickelt wurde. In der Street-Art-Szene ist die Koordination von Materialien (Pigmente, Steine, Quarz) oft chaotisch. Dieses Portal strukturiert den **Request-Prozess** durch ein minimalistisches, mobiles Interface.

### 🧬 Design-Philosophie: "Psychedelic Graffiti"
Das Design bricht mit traditionellen Corporate-Standards und nutzt eine **High-Contrast Acid-Palette**. Dies dient der Untersuchung von:
* **Barrierefreiheit:** Lesbarkeit unter schwierigen Lichtverhältnissen (z.B. Baustellen, Nachtarbeit).
* **Brand Identity:** Visuelle Synergie mit der Graffiti-Subkultur.
* **Micro-Interactions:** Intuitive Counter-Buttons für schnelle Mengenänderungen auf Touch-Displays.

---

## 🛠 Technische Spezifikationen
Um maximale Performance in instabilen mobilen Netzwerken zu gewährleisten, wurde auf schwere Frameworks verzichtet:

* **Sprachen:** HTML5, CSS3 (Custom Properties), Vanilla JavaScript (ES6+).
* **Architektur:** Event-gesteuerte DOM-Manipulation für die Mengensteuerung.
* **Datentransfer:** Asynchroner POST-Request via Web3Forms API (Serverless-Ansatz).
* **Sicherheit:** Integrierte CSRF-Prävention durch API-Key-Maskierung und verschlüsselte Redirect-Parameter.

---

## 🚀 Installation & Deployment
1. **Clone:** `git clone https://github.com/DEIN-USERNAME/PROJEKTNAME.git`
2. **Setup:** Web3Forms API-Key in `index.html` hinterlegen.
3. **Deploy:** Optimiert für das Hosting auf **Netlify** (automatisiertes CI/CD via GitHub Hook).

---

## 🔒 Security & Privacy Notes
Dieses Projekt speichert **keine** personenbezogenen Daten in einer lokalen Datenbank. Alle Anfragen werden verschlüsselt an den konfigurierten Endpunkt übertragen. Die generierte **Request-ID** dient zur zustandslosen Nachverfolgung ohne User-Tracking.

---
**Disclaimer:** *Dies ist ein Bildungsprojekt im Rahmen einer IT-Weiterbildung. Alle Produktbezeichnungen (z.B. "Weißer Quarz") beziehen sich auf fiktive Materialien für Kunstinstallationen.*
