<!--

author:   Volker Göhler
email:    volker.goehler@informatik.tu-freiberg.de
version:  0.0.1
language: de
narrator: Deutsch Female

edit: true
date: 2026-06-19

comment:  Übung Softwareentwicklung 06 -- Template

import: https://raw.githubusercontent.com/liascript-templates/plantUML/master/README.md

link:   https://raw.githubusercontent.com/vgoehler/LiaScript_CSS_Provider/refs/heads/main/dist/university.css

tags: [Sommersemester2026, Softwareentwicklung, Übung06]

-->

[![LiaScript Course](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/Ifi-Softwareentwicklung-SoSe2026/exercise-06/refs/heads/main/README.md)

# Aufgabe 06

Softwareentwicklung SoSe2026
============================

## Aufgabe

In der User Story ist die 

## **User Story: Digitale Flächenverwaltungsplattform für Bauvorhaben**

Als Bauamtsmitarbeiter möchte ich eine digitale Plattform zur Verwaltung von Bauflächen und -vorhaben nutzen, damit ich Bauanträge effizient bearbeiten, Flächen zuweisen und den Fortschritt von Bauprojekten nachverfolgen kann.

### **Akzeptanzkriterien**

1. **Grundlegende Flächenverwaltung**
====================

- Das System muss Grundstücke und Bauflächen veralten können (Flurstücknummer („0015 00012 001/002“ (Flur 0015, Flurstück 00012, Teilfläche 001/002)) Größe, Lage, aktuelle Nutzung (Gewerbe, Landwirtschaft, Forst, Wohnnutzung, Brachfläche, ...), Bebaubarkeit (ja, nein, auflagen). Ein Grundstück kann mehrere Bauflächen enthalten.
- Jede Fläche muss mit Metadaten wie B-Plan-Nummer ("BP-2022-089 – Wohngebiet Leipzig-Nord"), Bodenrichtwert ($500 €/m^2$) und Eigentümer verknüpft sein.
- Flächen müssen als „frei“, „reserviert“ oder „bebaut“ markiert werden können.

2. **Bauvorhaben verwalten**
====================

- Das System muss Bauvorhaben anlegen und verknüpfen können mit:
  - Antragsteller (Name, Kontaktdaten, Firma)
  - Geplante Nutzung (Wohngebäude, Gewerbe, Infrastruktur)
  - Zeitplan (Beginn, Fertigstellung)
  - Status (Antrag eingereicht, genehmigt, abgelehnt, in Bearbeitung, abgeschlossen)
- Jedes Bauvorhaben muss einer oder mehreren Flächen zugeordnet werden können.


## Agent-Workflow

Erstellen Sie zu Beginn ein GitHub-Issue, in dem Sie Kevin bitten, aus dieser User Story ein PlantUML-Klassendiagramm zu erstellen.

Kevin arbeitet auf einem eigenen Branch, ändert im  und erstellt eine Pull Request nach `main`. Kevin soll dabei auch den LiaScript-Course-Link auf Ihr studentisches Repository anpassen.

Reviewen Sie Kevins Pull Request. Lisa reviewed denselben Pull Request automatisch.
Kevin arbeitet Feedback erst ein, wenn für denselben PR-Stand sowohl Ihr Review als auch Lisas Review vorliegen. Der Pull Request wird erst gemerged, wenn beide Reviews genehmigt sind.

## Aufgabe: PlantUML-Dokumentaton

- [plantUML Editor](https://plantuml.com)

- paste and copy your code! Mit Reloads verlieren Sie Ihre Eingaben, daher vorher sichern!

```text @plantuml
@startuml

@enduml
```


