---
sidebar_position: 22
---

# Datenbanken

<!-- Datenbankabfrage, Datenpflege mit SQL erstel- len können

-   Tabellenstruktur (CREATE TABLE, ALTER TABLE)
-   Index (CREATE INDEX)
-   Manipulation (INSERT, UPDATE, DELETE)
-   Projektion (SELECT FROM)
-   Selektion (SELECT FROM ... WHERE) und (SELECT ...
    (SELECT ...))
-   Sortieren (ORDER BY)
-   Gruppieren (GROUP BY, HAVING)
-   Abfrage über mehrere Tabellen
-   Ausdrücke und Bedingungen
-   Aggregatfunktionen -->

## Primär- und Fremdschlüssel

-   Primärschlüssel: Eindeutiger Schlüssel zur Identifikation von Datensätzen in einer Tabelle (z.B. Kundennummer)
-   Fremdschlüssel: Schlüssel in einer Tabelle, der auf den Primärschlüssel einer anderen Tabelle verweist (z.B. Bestellnummer als Fremdschlüssel in der Tabelle "Bestellpositionen")
-   Beziehungen: Verbindung zwischen Tabellen über Primär- und Fremdschlüssel zur Abbildung von Datenabhängigkeiten

## Tabellenstruktur

-   Erstellung von Tabellen (CREATE TABLE)
-   Veränderung von Tabellen (ALTER TABLE)

## Index

-   Erstellung von Indizes zur Optimierung von Datenbankabfragen (CREATE INDEX)

## Manipulation

-   Einfügen von Daten (INSERT)
-   Aktualisierung von Daten (UPDATE)
-   Löschen von Daten (DELETE)

## Projektion

-   Selektion von Spalten aus einer Tabelle (SELECT FROM)

## Selektion

-   Selektion von Zeilen aus einer Tabelle mit Bedingungen (WHERE)
-   Selektion von Zeilen aus mehreren Tabellen mit Bedingungen (JOIN)

## Sortieren

-   Sortierung von Ergebnissen (ORDER BY)

## Gruppieren

-   Zusammenfassung von Daten nach bestimmten Kriterien (GROUP BY)
-   Filterung von Ergebnissen nach Gruppierung (HAVING)

## Abfrage über mehrere Tabellen

-   Verknüpfung von Daten aus verschiedenen Tabellen (JOIN)

## Ausdrücke und Bedingungen

-   Verwendung von logischen Operatoren (AND, OR, NOT)
-   Vergleichsoperatoren (>, <, =, !=)
-   Verwendung von Wildcards (%, \_)

## Aggregatfunktionen

-   Berechnung von statistischen Kennzahlen (SUM, AVG, COUNT, MAX, MIN)

## Beispiel-Fragen

-   Wie erstellt man eine neue Tabelle in SQL?
-   Was sind Indizes in einer Datenbank und wofür werden sie verwendet?
-   Wie fügt man Daten in eine Tabelle ein und wie aktualisiert oder löscht man diese?
-   Was ist der Unterschied zwischen Projektion und Selektion in SQL?
-   Wie verknüpft man Daten aus verschiedenen Tabellen in SQL?
-   Wie gruppiert man Daten in SQL und wofür wird dies verwendet?
-   Wie filtert man Ergebnisse nach Gruppierung in SQL?
-   Welche logischen und Vergleichsoperatoren gibt es in SQL und wie werden sie verwendet?
-   Was sind Aggregatfunktionen in SQL und welche Kennzahlen können damit berechnet werden?
-   Was ist ein Primärschlüssel in SQL und welche Funktion hat er?
-   Was ist ein Fremdschlüssel in SQL und wie wird er verwendet?
-   Wie werden Beziehungen zwischen Tabellen in SQL hergestellt und welche Arten von Beziehungen gibt es?
-   Was passiert mit Daten in einer Tabelle, wenn der zugehörige Datensatz in einer anderen Tabelle gelöscht wird (z.B. durch CASCADE)?
