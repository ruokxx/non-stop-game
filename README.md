# ⚡ NONSTOP – Partyspiel Begleit-App (PWA)

Eine eigenständige, rasante Web-App (Progressive Web App) für das Kartenspiel **Nonstop**, optimiert für iOS / iPhone (Vollbildmodus über den Home-Bildschirm) und komplett ohne App-Store-Zwang nutzbar.

🔗 **Live-App starten:** `https://ruokxx.github.io/non-stop-game/`

---

## 🎯 Features

* **🗣️ Deutsche Sprachausgabe (Text-to-Speech):** Liest jede Kategorie – sowie aktive Spezial-Runden – automatisch vor. Der Countdown startet erst, wenn die Ansage komplett beendet ist.
* **⏱️ Flexibler Runden-Timer:** Standardmäßig **10 Sekunden** mit visuellem Fortschrittsring, Ticken in den letzten 3 Sekunden und Game-Show-Buzzer bei Ablauf (im Setup anpassbar von 5 bis 30 Sekunden).
* **📚 Über 265 Kategorien:**
  * **225 Standard-Kategorien** für Familien- und Spieleabende
  * **42 Ü18-Kategorien** (wahlweise deaktiviert, gemischt oder exklusiv aktivierbar)
  * **Eigene Kategorien:** Direkt in der App hinzufügbar (lokale Speicherung im Browser)
* **🔥 30 Spezial-Runden (Chaos-Regeln):** Alle 8 Runden (Intervall einstellbar) wird automatisch eine zufällige Zusatzaufgabe ausgelöst – z. B. *Flüstern*, *Singen*, *Nicht lachen* oder *Doppelte Strafkarten*.
* **📱 Optimiert für iOS & Mobile:** Fixiertes Vollbild-Layout ohne Scrollen, eigenes App-Icon und offlinefähige Web-Audio-Sounds ohne externe MP3-Dateien.

---

## 📲 Installation auf dem iPhone (ohne App Store)

1. Öffne die **GitHub-Pages-URL** in **Safari** auf dem iPhone.
2. Tippe unten auf das **Teilen-Symbol** (Viereck mit Pfeil nach oben).
3. Wähle **„Zum Home-Bildschirm“** und bestätige mit **Hinzufügen**.
4. Die App startet ab sofort im Vollbildmodus wie eine native iOS-App.

> **Tipp:** Damit Sprachausgabe und Buzzer-Sounds auf dem iPhone zu hören sind, muss der seitliche Stummschalter deaktiviert sein.

---

## 🎲 Spielprinzip (Kurzregeln)

1. Jeder Spieler erhält eine feste Anzahl an **Buchstabenkarten** auf die Hand.
2. Tippe in der App auf **„Nächste Runde“** – die Kategorie wird angesagt.
3. Sobald der **10-Sekunden-Timer** startet, legen alle Spieler der Reihe nach (oder gleichzeitig nach Hausregel) passende Karten ab, indem sie einen Begriff zur Kategorie mit dem jeweiligen Anfangsbuchstaben nennen *(z. B. Kategorie: „Was gibt es zu trinken?“ → Karte **O** für „Orangensaft“)*.
4. Ertönt der **Buzzer**, endet die Runde. Wer bis dahin keine Karte ablegen konnte oder eine Spezial-Regel bricht, zieht eine Strafkarte.

---

## 📂 Projektstruktur

```text
├── index.html      # Komplette App (UI, Game-Logik, TTS, Web-Audio & Kategorien)
├── manifest.json   # PWA-Konfiguration für Vollbildmodus & Home-Bildschirm
├── icon.svg        # Vektor-App-Icon für iOS & Android
└── README.md       # Projektdokumentation
