# debuzz2

**Ein Django-basiertes Tool zur Verwaltung von Unternehmenskennzahlen.**

## Inhaltsverzeichnis
- [Einführung](#einführung)
- [Funktionen](#funktionen)
- [Installation](#installation)
- [Verwendung](#verwendung)


---

## Einführung

`debuzz2` ist ein Python-Django-Projekt, das es ermöglicht, Unternehmenskennzahlen einfach zu verwalten und zu berechnen. Es bietet eine benutzerfreundliche Weboberfläche, um Daten zu kategorisieren und verschiedene betriebswirtschaftliche Berechnungen durchzuführen.

---

## Funktionen

- **Kategorisierte Unternehmenskennzahlen:** Anzeige und Verwaltung von Kennzahlen wie Rentabilität, Liquidität, etc.
- **Taschenrechner:** Berechnung wichtiger betriebswirtschaftlicher Kennzahlen (z. B. ROI, Break-Even Point).
- **Einfache Navigation:** Über eine klar strukturierte Weboberfläche.

---


   
Ein Django-basiertes Tool zur Verwaltung von Unternehmenskennzahlen.

## Installation und Nutzung

Folge den Schritten, um das Projekt zu starten und zu nutzen:

### 1. Virtuelle Umgebung erstellen und aktivieren

```bash
python3 -m venv .venv
source .venv/bin/activate  # Auf Windows: .venv\Scripts\activate
```

### 2. Abhängigkeiten installieren

```bash
pip install -r requirements.txt
```

### 3. Datenbank migrieren

```bash
python manage.py makemigrations
python manage.py migrate
```

### 4. Server starten

```bash
python manage.py runserver
```

### 5. Anwendung nutzen

Nach dem Start des Servers ist die Anwendung unter `http://127.0.0.1:8000/` verfügbar. 

#### Hinweis:
Um auf die Hauptfunktionen zuzugreifen, füge `/kpi` zur URL hinzu: 

```
http://127.0.0.1:8000/kpi
```

Besuche anschließend [http://127.0.0.1:8000](http://127.0.0.1:8000) in deinem Browser.

---

## Verwendung

### Navigationsoptionen
- **Home:** Übersicht und Einführung in das Tool.
- **Kategorien:** Zeigt alle verfügbaren Unternehmenskennzahlen nach Kategorien sortiert.
- **Taschenrechner:** Berechnet wichtige betriebswirtschaftliche Kennzahlen.
