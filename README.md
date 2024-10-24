# Klassifizierung von Filmen mittels maschinellem Lernen

## Inhaltsverzeichnis
- [Beschreibung](#Beschreibung)
- [Installation](#Installation)
- [Daten Sammeln](#DatenSammeln)
- [Modelltraining](#Modelltraining)
- [Ergebnisse](#Ergebnisse)



## Beschreibung
Logistic Regression, K-Nearest Neighbors (KNN) und neuronale Netzwerke in PyTorch sind die drei gängigen maschinellen Lernalgorithmen, die bei der Klassifizierung von Filmen anhand ihrer Overviews und Genres verwendet werden. Der Schwerpunkt liegt auf der Frage, welcher Algorithmus auf der Grundlage der Filmsprache die beste Leistung bei der Vorhersage der Filmkategorien erbringt. Dies soll verdeutlichen, welche Herangehensweise am besten geeignet ist, um die sprachspezifischen Merkmale von Filmen zur Einordnung in die Klassifikation zu nutzen.

## Installation

Sie können die erforderlichen Pakete mit dem folgenden Befehl in Ihrer Umgebung installieren:

```bash
pip install -r requirements.txt
```

## DatenSammeln
Die Daten stammen von der Webseite 'The Movie Database'. Durch das Erstellen eines Accounts bzw. über die API kann man verschiedene Variablen (z. B. den Titel des Films, das Veröffentlichungsdatum, usw.) erhalten. Die Daten wurden anschließend in einer CSV-Datei gespeichert. Danach war es notwendig, weitere Schritte durchzuführen, bevor die Daten für die Machine-Learning-Modelle verwendet werden konnten. Beispielsweise wurden Zeilen mit NaN-Werten entfernt, die textuellen Daten wurden mit NLP-Techniken verarbeitet und durch Oversampling und Undersampling basierend auf der Anzahl der Filme pro Sprache ausgeglichen.

## Modelltraining
## Ergebnisse 

