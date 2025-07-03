TicTacToe



Dieses Projekt ist eine einfache Implementierung des TicTacToe-Spiels in Java.



Inhalt

\- Über das Projekt

\- Installation

\- Verwendung

\- Features

\- CI/CD

\- Projektstruktur



Über das Projekt



Dieses Projekt implementiert ein Konsolen-basiertes TicTacToe-Spiel für zwei Spieler. Spieler geben ihre Züge durch Koordinaten ein. Das Spiel erkennt automatisch einen Gewinner oder ein Unentschieden und erlaubt das Starten eines neuen Spiels.



Installation



Voraussetzungen:

\- Java Development Kit (JDK) 11 oder höher

\- Apache Maven



Schritte zur Installation:

1\. Repository klonen:

&nbsp;  git clone https://github.com/tarekh-97/tictactoe-java.git

&nbsp;  cd tictactoe-java/tictactoe



2\. Projekt bauen:

&nbsp;  mvn clean package



Verwendung



Nach dem erfolgreichen Build kann das Spiel ausgeführt und über die Konsole gespielt werden.



Spielanleitung:

\- Zwei Spieler spielen abwechselnd.

\- Züge werden eingegeben durch Angabe von Zeile und Spalte (z. B. "1 1" für die Mitte).

\- Nach jedem Zug wird das aktuelle Spielfeld angezeigt.

\- Das Spiel erkennt automatisch einen Sieg oder ein Unentschieden.

\- Nach dem Ende kann ein neues Spiel gestartet werden.



Features



\- Zwei-Spieler-Modus über Konsole

\- Automatische Spielend-Erkennung (Sieg/Unentschieden)

\- Dynamische Spielfeldanzeige

\- Möglichkeit zum Neustart

\- Spielerwechsel nach jedem Zug



CI/CD



Die GitHub Actions Konfiguration befindet sich in .github/workflows/ci.yml. Sie sorgt dafür, dass das Projekt bei jedem Push und Pull Request automatisch gebaut und getestet wird.



Projektstruktur



tictactoe/

├── src/

│   ├── main/java/

│   │   ├── Board.java

│   │   ├── Player.java

│   │   └── TicTacToe.java

│   └── test/java/

│       ├── BoardTest.java

│       ├── PlayerTest.java

│       └── TicTacToeTest.java

├── pom.xml

└── .github/workflows/ci.yml



