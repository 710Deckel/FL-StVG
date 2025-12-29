# ⚖️ FL-StVG - Straßenverkehrsgesetz Editor

**Fahrlehrer-Ausbildung FL-BE_07/25**  
Verkehrsinstitut Schielein Nürnberg

---

## 📚 Über dieses Repository

Dieses Repository enthält die Daten für den **StVG Editor** - ein professionelles Werkzeug zur systematischen Aufbereitung des Straßenverkehrsgesetzes (StVG) für die Fahrlehrer-Ausbildung.

Der Editor ermöglicht die strukturierte Erfassung von Gesetzestexten, Praxisbeispielen und deren Synchronisation über GitHub.

---

## 📂 Repository-Struktur

```
FL-StVG/
├── README.md       (diese Datei - Projektbeschreibung)
└── data.json       (StVG-Daten, automatisch synchronisiert vom Editor)
```

---

## 🔄 Daten-Synchronisation

Die Datei `data.json` wird **automatisch** vom StVG Editor synchronisiert:

- ✅ Jedes Speichern im Editor aktualisiert diese Datei
- ✅ Änderungen werden mit Zeitstempel versioniert
- ✅ Team-Kollaboration möglich (mehrere Nutzer, ein Repository)

**⚠️ WICHTIG:** Die `data.json` sollte **nicht manuell bearbeitet** werden!  
Alle Änderungen bitte nur über den StVG Editor vornehmen.

---

## 🛠️ Verwendung

### 1. Repository-Setup (einmalig)
- Repository erstellt: ✅ `710Deckel/FL-StVG`
- README.md hochgeladen: ✅

### 2. Editor-Verwendung
- HTML-Datei lokal öffnen (`stvg-editor.html`)
- GitHub Token eingeben (einmalig)
- Paragraphen hinzufügen und speichern
- Automatische Synchronisation erfolgt

### 3. Token-Anforderungen
Der verwendete Token benötigt folgende Berechtigungen:
- ✅ `repo` (Full control of private repositories)

---

## 📋 Datenstruktur

Die `data.json` enthält alle StVG-Paragraphen im folgenden Format:

```json
{
  "paragraphen": [
    {
      "id": "timestamp",
      "gesetz": "StVG",
      "nummer": "§ 1",
      "titel": "Zulassung",
      "gesetzestext": "...",
      "quelle": "https://...",
      "praxisbeispiele": [
        {
          "titel": "Beispiel",
          "klasse": "ALLE",
          "beschreibung": "...",
          "wichtigkeit": "HIGH"
        }
      ]
    }
  ]
}
```

---

## 🎯 Features des Editors

- **2-Spalten-Layout:** Gesetzestext | Praxisbeispiele
- **GitHub Auto-Sync:** Automatische Synchronisation
- **Template-System:** Vordefinierte Beispiele für häufige Fälle
- **Badge-System:** CRITICAL (rot) | HIGH (orange) | BANAL (grün)
- **PDF-Export:** Professionelle Druckausgabe
- **Import/Export:** JSON-Backup-System
- **Keyboard Shortcuts:** Strg+S zum Speichern

---

## 🔗 Weitere Fahrlehrer-Tools

Dieses Repository ist Teil einer systematischen Tool-Suite für die Fahrlehrer-Ausbildung:

- [📘 FL-StVO](https://github.com/710Deckel/stvo-teleprompter) - StVO Teleprompter mit Erläuterungen
- [🚛 FL-FPersV-EG-VO](https://github.com/710Deckel/FL-FPersV-EG-VO) - Fahrpersonalverordnung & EU-Verordnung
- [⚖️ FL-StVG](https://github.com/710Deckel/FL-StVG) - Straßenverkehrsgesetz (dieses Repository)
- [🔧 FL-StVZO](https://github.com/710Deckel/FL-StVZO) - Straßenverkehrs-Zulassungs-Ordnung
- [📋 FL-FeV](https://github.com/710Deckel/FL-FeV) - Fahrerlaubnis-Verordnung
- [🚗 FL-FZV](https://github.com/710Deckel/FL-FZV) - Fahrzeug-Zulassungsverordnung

---

## 📝 Lizenz & Verwendung

**Projekt:** Fahrlehrer-Ausbildung FL-BE_07/25  
**Ersteller:** Justin Lee Probis   
**Zweck:** Ausbildung und Podcast "Fahrlehrer Inside"

Dieses Tool und die Daten sind für **Ausbildungszwecke** erstellt.

---

## 📞 Kontakt & Feedback

Bei Fragen, Problemen oder Verbesserungsvorschlägen:
- GitHub Issues in diesem Repository
- Feedback über das Tool (Thumbs Down Button)

---

**Erstellt mit ❤️ für die Fahrlehrer-Ausbildung**

*Letzte Aktualisierung: Dezember 2024*
