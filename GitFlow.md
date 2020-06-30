Git-Kenntnisse vertiefen. Hier ist der aktuelle Git Flow aus der Übung.

Projekt klonen:
```git clone https://github.com/andkopp/andkopp.github.io.git```

Inhalt der Datei in einem neuen Branch ändern:
1. Neuen Feature-Branch erstellen: ```git branch featureX_title```
2. Auf lokalem Rechner in diesen Branch wechseln: ```git checkout featureX_title```
3. Dateien erstellen oder ändern
4. Geändertere Dateien vormerken/stagen: ```git add dateiname```
5. Änderungen commiten: ```git commit -m "Commit-Nachricht"```
6. Änderungen pushen: ```git push``` bzw. ```git push --set-upstream origin featureX_title```

Anschließend auf github:
1. Pull Request erstellen und über ```#``` den Issue referenzieren.
2. Pull Request mergen und Feature-Branch löschen.

Anschließend lokal:
1. Auf Master-Branch wechseln: ```git checkout master```
2. Feature-Branch auch lokal löschen: ```git branch -d featureX_title```
3. Lokales Repository aus remote (github) aktualisieren: ```git pull```
