# Projektübersicht

Im Rahmen eines Studienprojekts im Bereich Softwareentwicklung habe ich die historischen Finanzdaten des Spielwarenherstellers Mattel, Inc. analysiert.

Ziel war es, Kursentwicklungen über einen längeren Zeitraum zu untersuchen, statistische Kennzahlen zu berechnen und die Ergebnisse mithilfe verschiedener Visualisierungen aufzubereiten.

Für die Analyse habe ich historische Aktiendaten mithilfe der Python-Bibliothek yfinance abgerufen und anschließend mit pandas verarbeitet und ausgewertet.

# Durchgeführte Analysen

Das Notebook umfasst verschiedene Untersuchungen zur historischen Kursentwicklung und zum Rendite- und Risikoverhalten der Mattel-Aktie.

1. Historische Kursentwicklung

- Analyse der Aktienkurse von 1993 bis Ende 2024
- Untersuchung von Tageshöchst- und Tagestiefstkursen
- Darstellung der langfristigen Kursentwicklung

2. Renditeanalyse

- Berechnung täglicher Renditen mithilfe von prozentualen Kursveränderungen
- Untersuchung jährlicher Renditen
- Visualisierung positiver und negativer Handelstage

3. Risikoanalyse

- Berechnung der rollierenden Standardabweichung über einen Zeitraum von 252 Handelstagen
- Untersuchung historischer Kursschwankungen
- Betrachtung ausgewählter Kursrückgänge

4. Datenvisualisierung

- Kursverläufe und Handelsvolumen
- 30- und 90-Tage-Durchschnittslinien
- Histogramm täglicher Renditen
- Darstellung positiver und negativer Handelstage
- Vergleich verschiedener historischer Zeitabschnitte

5. Historische Betrachtung

Zusätzlich habe ich ausgewählte Zeitabschnitte der Unternehmensgeschichte betrachtet, um die langfristige Kursentwicklung in einen historischen Zusammenhang zu stellen.

# Datenquelle

Die historischen Aktiendaten werden über die Python-Bibliothek yfinance abgerufen.

Unternehmen: Mattel, Inc.

Börsenkürzel: MAT

Datenquelle: Yahoo Finance

Untersuchungszeitraum: 01.01.1993 bis 31.12.2024

# Projekt ausführen

Das Projekt liegt als Jupyter Notebook vor.

> Voraussetzungen:

- Python

- Jupyter Notebook oder JupyterLab

> Benötigte Bibliotheken installieren: pip install yfinance pandas matplotlib jupyter

> Notebook starten: jupyter notebook

Anschließend kann Projektpräsentation_Mattel (1).ipynb geöffnet und schrittweise ausgeführt werden. Für den Datenabruf wird eine Internetverbindung benötigt.

# Was ich bei diesem Projekt gelernt habe

Durch die Arbeit an diesem Projekt konnte ich meine praktischen Kenntnisse in Python und der Datenanalyse erweitern.

Besonders beschäftigt habe ich mich mit:

- dem Abrufen externer Finanzdaten
- der Verarbeitung und Aufbereitung von Datensätzen mit pandas
- der Berechnung statistischer Kennzahlen
- der Untersuchung von Rendite und historischen Kursschwankungen
- der Erstellung und Interpretation von Datenvisualisierungen
- der strukturierten Dokumentation einer Datenanalyse in Jupyter Notebook
  
Das Projekt war eine meiner ersten praktischen Erfahrungen mit Python und hat mir einen Einblick in die Möglichkeiten der datenbasierten Analyse gegeben.

> Hinweis:
Dieses Projekt wurde im Rahmen meines Studiums zu Lern- und Präsentationszwecken erstellt. Die dargestellten Analysen dienen der historischen Betrachtung und stellen keine Anlageberatung oder Investitionsempfehlung dar.
