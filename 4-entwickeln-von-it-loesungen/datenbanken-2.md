---
sidebar_position: 3
---

# Datenbanken

<!-- Datenbanken modellieren und erstellen

-   Relationale und nicht-relationale Datenbanken,
    NoSQL Datenbanken
-   Datentypen: Boolesche Werte, Ganzzahl, Gleitkommawerte, Währung, Datumswerte, Texte fester und
    variabler Länge, BLO, Geokoordinaten
-   Normalisieren, 1. bis 3. Normalform
-   ER-Diagramm, Attribute, Beziehungen, Kardinalitäten, referenzielle Integrität, Aktualisierungsweitergabe, Löschweitergabe, Primärschlüssel, Fremdschlüssel
-   Datenbankabfrage, Datenpflege
-   Tabellenstruktur (CREATE TABLE, ALTER TABLE),
    Index (CREATE INDEX), Manipulation (INSERT, UPDATE, DELETE), Projektion (SELECT FROM) Selektion
    (SELECT FROM ... WHERE) und (SELECT ... (SELECT
    ...)), Sortieren (ORDER BY), Gruppieren (GROUP BY,
    HAVING)
-   Abfrage über mehrere Tabellen (JOIN)
-   Ausdrücke und Bedingungen
-   Aggregat-Funktionen, z. B. SUM
-   OpenData, API-Schnittstellen -->

### Relationale und nicht-relationale Datenbanken, NoSQL Datenbanken

-   Relationale Datenbanken speichern Daten in Tabellen, die durch Beziehungen miteinander verbunden sind
-   Nicht-relationale Datenbanken speichern Daten in hierarchischer, netzwerkartiger oder objektorientierter Struktur
-   NoSQL-Datenbanken sind eine spezielle Art nicht-relationaler Datenbanken, die eine höhere Skalierbarkeit und Flexibilität bieten

### Datentypen

-   Boolesche Werte: ja/nein oder wahr/falsch
-   Ganzzahl: ganze Zahlen ohne Nachkommastellen
-   Gleitkommawerte: Zahlen mit Nachkommastellen
-   Währung: Beträge in einer bestimmten Währung
-   Datumswerte: Datum und Uhrzeit
-   Texte fester und variabler Länge: Textinformationen mit fester oder variabler Länge
-   BLOB: Binäre große Objekte, wie Bilder oder Videos
-   Geokoordinaten: Längen- und Breitengrade für die Standortbestimmung

### Normalisieren, 1. bis 3. Normalform

-   Normalisieren bedeutet, die Daten so zu strukturieren, dass keine Redundanzen und Inkonsistenzen auftreten
-   Die 1. Normalform verlangt, dass jeder Wert in einer Spalte atomar sein muss
-   Die 2. Normalform verlangt, dass jede Nichtschlüssel-Spalte funktional von jedem Schlüsselkandidaten abhängt
-   Die 3. Normalform verlangt, dass jede Nichtschlüssel-Spalte funktional von jedem Schlüssel abhängt

### ER-Diagramm, Attribute, Beziehungen, Kardinalitäten, referenzielle Integrität, Aktualisierungsweitergabe, Löschweitergabe, Primärschlüssel, Fremdschlüssel

-   ER-Diagramm: graphische Darstellung von Entitäten, Attributen und Beziehungen in einer Datenbank
-   Attribute: Eigenschaften einer Entität
-   Beziehungen: Verbindungen zwischen Entitäten
-   Kardinalitäten: Anzahl der Entitäten, die an einer Beziehung beteiligt sind (1:1, 1:n, n:m)
-   Referenzielle Integrität: Sicherstellung der Beziehungskonsistenz in einer Datenbank
-   Aktualisierungsweitergabe: Aktualisierung von Fremdschlüssel-Werten bei Änderungen an Primärschlüssel-Werten
-   Löschweitergabe: Löschung von Fremdschlüssel-Werten bei Löschung von Primärschlüssel-Werten
-   Primärschlüssel: eindeutiger Wert zur Identifizierung einer Entität
-   Fremdschlüssel: Attribut in einer Entität, das auf den Primärschlüssel einer anderen Entität verweist

## Datenbankabfrage, Datenpflege

-   Datenabfrage: Abfrage von Daten aus der Datenbank
-   Datenpflege: Einfügen, Aktualisieren und Löschen von Daten in der Datenbank

## Tabellenstruktur

-   CREATE TABLE: Anlegen von Tabellen in der Datenbank
-   ALTER TABLE: Ändern von Tabellenstrukturen
-   CREATE INDEX: Erstellen von Indizes für schnelle Datenabfragen
-   INSERT: Einfügen von Datensätzen in die Tabelle
-   UPDATE: Aktualisieren von Datensätzen in der Tabelle
-   DELETE: Löschen von Datensätzen aus der Tabelle
-   SELECT FROM: Abfrage von Daten aus einer Tabelle

## Selektion, Sortieren, Gruppieren

-   WHERE: Filtern von Datensätzen nach bestimmten Kriterien
-   ORDER BY: Sortieren von Datensätzen nach bestimmten Kriterien
-   GROUP BY: Gruppieren von Datensätzen nach bestimmten Kriterien
-   HAVING: Filtern von gruppierten Daten nach bestimmten Kriterien

## JOIN

-   Verknüpfen von Daten aus verschiedenen Tabellen

## Ausdrücke und Bedingungen

-   Ausdrücke: mathematische und logische Ausdrücke für Datenabfragen
-   Bedingungen: Einschränkungen für Datenabfragen

## Aggregat-Funktionen

-   SUM: Summieren von Daten
-   COUNT: Zählen von Datensätzen
-   AVG: Berechnen des Durchschnitts von Daten
-   MAX: Bestimmen des höchsten Wertes von Daten
-   MIN: Bestimmen des niedrigsten Wertes von Daten

## OpenData, API-Schnittstellen

-   OpenData: öffentlich zugängliche Daten für Datenanalyse und -verarbeitung
-   API-Schnittstellen: Schnittstellen für den Zugriff auf Daten von externen Systemen

## Beispiel-Fragen

-   Was sind die Unterschiede zwischen relationalen und nicht-relationalen Datenbanken?
-   Welche Datentypen können in einer Datenbank verwendet werden?
-   Was bedeutet es, eine Datenbank zu normalisieren?
-   Wie können Daten in der 3. Normalform organisiert werden?
-   Was sind die Vorteile von NoSQL-Datenbanken gegenüber relationalen Datenbanken?
-   Was ist eine Datenbankabfrage und wie kann sie in SQL umgesetzt werden?
-   Wie kann die Struktur einer Tabelle in einer Datenbank geändert werden?
-   Wie können Daten aus mehreren Tabellen verknüpft werden?
-   Wie können Daten nach bestimmten Kriterien sortiert oder gruppiert werden?
-   Was sind Aggregat-Funktionen und wie können sie eingesetzt werden?
