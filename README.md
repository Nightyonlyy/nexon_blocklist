# Nexon/Vivox Blocklist (für The First Descendant)

Diese Liste blockiert diverse Tracking- und Telemetrie-Endpunkte von **Nexon**, **Vivox** und zugehörigen Diensten. Sie ist primär für Nutzer gedacht, die Nexon-Spiele nutzen, aber bestimmte Datenverbindungen unterbinden möchten.

---

## 🔗 Blocklisten-URL

**Direkter Link zur Blockliste (Raw Format):**

https://raw.githubusercontent.com/Nightyonlyy/nexon_blocklist/main/anit_nexon.txt


---

## 📥 Verwendung

### 🛡️ AdGuard

1. Öffne das **AdGuard Dashboard**.
2. Gehe zu **Filter → Benutzerdefinierte Filter**.
3. Klicke auf **Filter hinzufügen**.
4. Gib einen Namen ein (z. B. `Nexon Blocklist`) und verwende diesen Link:
https://raw.githubusercontent.com/Nightyonlyy/nexon_blocklist/main/anit_nexon.txt

5. Speichern & aktivieren.

---

### 📦 Pi-hole

1. Öffne die **Pi-hole Admin-Oberfläche**.
2. Navigiere zu **Group Management → Adlists**.
3. Füge dort die URL als neue Liste hinzu:
https://raw.githubusercontent.com/Nightyonlyy/nexon_blocklist/main/anit_nexon.txt

4. Klicke auf **Add**.
5. Danach im Terminal oder Admin-Bereich `pihole -g` ausführen, um die Listen neu zu laden.

---

## ℹ️ Hinweis

Diese Liste blockiert Verbindungen, die ggf. für Online-Funktionen von Spielen notwendig sind. Falls etwas nicht mehr wie erwartet funktioniert, kannst du einzelne Domains auskommentieren (mit `#` am Anfang der Zeile).

---

## ✍️ Mitmachen

Pull Requests für zusätzliche Domains oder Korrekturen sind willkommen!


Quelle:
https://gameindustry.eu/en/search/?suchbegriff=The+First+Descendant
