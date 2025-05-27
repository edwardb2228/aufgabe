# Git Befehle – Übersicht und Erklärung

## 🔧 Einrichtung

### Git installieren
Lade Git von https://git-scm.com herunter und installiere es.

### Benutzername und E-Mail festlegen
```bash
git config --global user.name "Dein Name"
git config --global user.email "deine@email.de"
```
---
## 📁 Repository erstellen

### Neues Repository starten
```bash
git init
```
Erstellt ein neues Git-Repository im aktuellen Ordner.

### Vorhandenes Repository klonen
```bash
git clone https://github.com/username/repo-name.git
```
Lädt ein Projekt von GitHub auf deinen Rechner.

---
## 📝 Änderungen verfolgen

### Status anzeigen
```bash
git status
```
Zeigt, was geändert wurde und was bereit zum Commit ist.

### Datei zum Commit vormerken
```bash
git add dateiname
```
Stellt Git die Datei für den nächsten Commit bereit.

### Alle Dateien zum Commit vormerken
```bash
git add .
```
Fügt alle geänderten Dateien hinzu.

---
## 💾 Änderungen speichern

### Commit erstellen
```bash
git commit -m "Nachricht"
```
Speichert die vorgemerkten Änderungen mit einer Nachricht.

---

## 🔄 Änderungen übertragen

### Repository mit GitHub verbinden
```bash
git remote add origin https://github.com/username/repo-name.git
```

### Änderungen hochladen (push)
```bash
git push
```

