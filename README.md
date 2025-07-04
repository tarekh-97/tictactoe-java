# TicTacToe

Dieses Projekt ist eine einfache Implementierung des TicTacToe-Spiels in Java.

Inhalt

- [Über das Projekt](#über-das-projekt)
- [Installation](#installation)
- [Verwendung](#verwendung)
- [Features](#features)
- [CI/CD](#cicd)
- [Projektstruktur](#projektstruktur)

## Über das Projekt

Dieses Projekt implementiert ein TicTacToe-Spiel, das über die Konsole gespielt werden kann. Es unterstützt zwei Spieler, die abwechselnd ihre Züge machen, bis entweder einer der Spieler gewinnt oder das Spiel unentschieden endet.

## Installation

1. Voraussetzungen:
- Java Development Kit (JDK) 11 oder höher
- Apache Maven

2.  Schritte zur Installation:
Klone das Repository:
git clone https://github.com/tarekh-97/tictactoe-java.git
cd tictactoe-java

## Verwendung

1. Starten des Spiels:
- Öffne die GitHub-Webseite des Projekts: https://github.com/tarekh-97/tictactoe-java.git
- Wechsle zum Actions-Tab.
- Klicke auf den letzten erfolgreichen Workflow-Run unter TicTacToe CI (Event: push, Branch: main).
- Scrolle im Details-Bereich nach unten zum Abschnitt Artifacts.
- Klicke auf tictactoe-jar → Download ZIP.
- Entpacke das heruntergeladene ZIP-Archiv. Du findest darin die Datei:
  tictactoe-1.0-SNAPSHOT.jar
- Öffne ein Terminal (CMD oder PowerShell) und wechsle in den Ordner mit der JAR-Datei:
  cd /pfad/zum/entpackten/ordner
- Starte das Spiel mit:
  java -jar tictactoe-1.0-SNAPSHOT.jar
- Das Spiel startet im Terminal, Spieler X beginnt.

2. Spielanleitung:
- Das Spiel wird im Terminal gespielt. Spieler geben ihre Züge ein, indem sie die Reihe und die Spalte für ihren Zug angeben (z.B., "1 1" für die Mitte).

## Features

- Spielzug machen: Spieler können abwechselnd ihre Züge machen.
- Spielbrett anzeigen: Das Spielbrett wird nach jedem Zug aktualisiert angezeigt.
- Spielende erkennen: Das Spiel erkennt automatisch, wenn ein Spieler gewonnen hat oder das Spiel unentschieden endet.
- Neues Spiel starten: Nach dem Ende eines Spiels kann ein neues Spiel gestartet werden, ohne die Anwendung neu zu starten.
- Spielerwechsel: Nach jedem Zug wechselt das Spiel automatisch den Spieler.

## Workflow-Datei:
Ein GitHub Actions–Workflow in .github/workflows/ci.yml führt bei jedem Merge in main folgende Schritte aus:
- Projekt bauen & Tests ausführen
- JAR erzeugen
- JAR als Artifact tictactoe-jar bereitstellen
Das heruntergeladene Artifact entspricht der oben beschriebenen JAR.

## Projektstruktur
src/main/java: Enthält den Quellcode des Projekts.
src/test/java: Enthält die Unit-Tests für das Projekt.
.github/workflows: Enthält die GitHub Actions Workflow-Datei für CI/CD.
pom.xml: Maven Projektdatei, die Abhängigkeiten und Build-Konfigurationen definiert.


Tarek Hitalani - Ali Ahmadi
