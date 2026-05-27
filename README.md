# KI-Sprachcoach – Mein Alltag

Ein KI-gestütztes Lernsystem, das echte Alltagssituationen automatisch in personalisierte Spanischlektionen verwandelt.

Das System analysiert Fotos und Sprachmemos aus dem Alltag und erstellt daraus kontextbasierte Lerninhalte, Übersetzungen und tägliche Wiederholungen für nachhaltiges Langzeitlernen-  mit genau den Wörtern und Ausdrücken, die einem im eigenen Alltag tatsächlich begegnen.

---

## Features

- Fotoanalyse mit KI
- Sprachmemo-Transkription
- Automatische Lernmaterialien
- Personalisierte Wiederholungen
- Telegram-Integration
- Tägliche Lernsessions
  
## Workflows

Das Projekt besteht aus zwei n8n-Workflows:

### 1. KI-Sprachcoach für den Alltag

Dieser Workflow verarbeitet Fotos und Sprachmemos aus Telegram, analysiert sie mit KI und speichert relevante Lerninhalte in Google Sheets.

<img width="1587" height="743" alt="transform-your-daily-life-into-spanish-lessons png" src="https://github.com/user-attachments/assets/cdd816f5-72ec-404f-89e2-a67a4aae5224" />

### 2. Tägliches Wiederholungssystem

Dieser Workflow startet automatisch jeden Morgen, lädt die Wörter vom Vortag aus Google Sheets und erstellt daraus eine kurze Lernsession per Telegram.

<img width="1344" height="711" alt="daily-lessons png" src="https://github.com/user-attachments/assets/504f1641-a5cc-4110-a402-db21b941c40d" />

## Funktionen

### Alltagssituationen analysieren

Das System verarbeitet reale Situationen aus dem Alltag, zum Beispiel:

- Schilder
- Flyer
- Formulare
- Gespräche
- Sprachmemos
- alltägliche Situationen in Spanien

---

### KI-gestützte Sprachanalyse

Die KI erkennt automatisch:

- wichtige Wörter
- Kontext und Bedeutung
- reale Alltagssituationen
- passende Antwortmöglichkeiten
- natürliche Formulierungen

---

### Personalisierte Lerninhalte

Aus echten Situationen entstehen automatisch:

- Übersetzungen
- Vokabelerklärungen
- Beispielsätze
- Mini-Lektionen
- alltagstaugliche Formulierungen

---

### Tägliche Lernimpulse

Ein separates Wiederholungssystem:

- lädt Wörter vom Vortag
- erstellt neue Lernimpulse
- wiederholt wichtige Begriffe
- unterstützt Langzeitlernen

---

# Systemarchitektur

Das Projekt besteht aus zwei KI-Workflows.

## 1. KI-Sprachcoach für den Alltag

Verarbeitet:
- Bilder
- Sprachmemos
- Alltagssituationen

Erstellt:
- Lernmaterial
- Übersetzungen
- Vokabeln
- kontextbasierte Erklärungen

---

## 2. Tägliches Wiederholungssystem

Automatisiert:
- tägliche Lernsessions
- Wiederholung vom Vortag
- Mini-Lektionen
- Telegram-Lernimpulse

---

# Technologien

- n8n
- OpenAI API
- Telegram Bot API
- Google Sheets
- OCR / Bildanalyse
- Sprachtranskription

---

# Beispiel

## Alltagssituation

Foto eines spanischen Flyers oder Schildes.

## KI-Ausgabe

- Erklärung der Situation
- deutsche Übersetzung
- wichtige Wörter
- passende Antwortmöglichkeiten
- tägliche Wiederholung am nächsten Morgen

---

# Erweiterungsmöglichkeiten

Geplante Erweiterungen:

- weitere Sprachen
- personalisierte Lernprofile
- Spaced Repetition
- mobile App
- Sprachstatistiken
- adaptive Lernpläne

---

# Idee des Projekts

Das Ziel des Projekts ist:

> Spanisch direkt aus echten Alltagssituationen zu lernen – nicht aus künstlichen Schulbuchübungen.

Der eigene Alltag wird automatisch zu einer personalisierten Sprachlektion.
