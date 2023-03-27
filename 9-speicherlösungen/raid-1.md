---
sidebar_position: 5
---

# RAID

# Redundant Array Of Disks

## RAID 0

-   Striping: Aufteilung der Daten auf mehrere Festplatten für eine höhere Geschwindigkeit
-   Keine Redundanz: Keine Datenwiederherstellung möglich, bei Ausfall einer Festplatte gehen alle Daten verloren

## RAID 1

-   Spiegelung: Duplizierung der Daten auf zwei Festplatten für eine höhere Ausfallsicherheit
-   Redundanz: Daten können bei Ausfall einer Festplatte wiederhergestellt werden
-   Halbierte Kapazität: Nur die Hälfte der Gesamtkapazität kann genutzt werden

## RAID 5

-   Block-Level Striping mit Paritätsinformationen: Aufteilung der Daten auf mehrere Festplatten und Speicherung von Paritätsinformationen für eine höhere Ausfallsicherheit und Datenwiederherstellung
-   Redundanz: Daten können bei Ausfall einer Festplatte wiederhergestellt werden
-   Effiziente Nutzung: 75% der Gesamtkapazität können genutzt werden

## RAID 10

-   Kombination aus RAID 1 und RAID 0: Spiegelung der Daten auf mehreren Festplatten für höhere Ausfallsicherheit und Striping der Daten für höhere Geschwindigkeit
-   Redundanz: Daten können bei Ausfall einer Festplatte wiederhergestellt werden
-   Effiziente Nutzung: 50% der Gesamtkapazität können genutzt werden

## RAID 6

-   Block-Level Striping mit doppelter Parität: Aufteilung der Daten auf mehrere Festplatten und Speicherung von doppelter Parität für höhere Ausfallsicherheit und Datenwiederherstellung bei Ausfall von bis zu zwei Festplatten
-   Redundanz: Daten können bei Ausfall von bis zu zwei Festplatten wiederhergestellt werden
-   Effiziente Nutzung: 67% der Gesamtkapazität können genutzt werden

## JBOD

-   Just a Bunch of Disks: Zusammenfassung mehrerer Festplatten zu einem großen virtuellen Laufwerk ohne RAID-Funktionalität
-   Keine Redundanz: Keine Datenwiederherstellung möglich, bei Ausfall einer Festplatte gehen alle Daten verloren
-   Volle Kapazität: Die gesamte Kapazität aller Festplatten kann genutzt werden

## Berechnung

-   Gesamtkapazität: Kapazität einer Festplatte \* Anzahl der Festplatten
-   Effektive Kapazität: Gesamtkapazität - Redundanz-Kapazität (bei RAID 1, 5, 6, 10)

## Beispiel-Fragen

-   Was ist RAID und welche Vorteile bietet es?
-   Was ist der Unterschied zwischen RAID 0 und RAID 1?
-   Wie funktioniert RAID 5 und wie erfolgt die Datenwiederherstellung bei Ausfall einer Festplatte?
-   Was ist RAID 10 und wie unterscheidet es sich von RAID 1 und RAID 0?
-   Was ist JBOD und welche Vorteile bietet es im Vergleich zu RAID?
-   Wie wird die effektive Kapazität bei RAID 5 berechnet?
