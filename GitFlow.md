Git-Kenntnisse vertiefen. Hier ist der aktuelle Git Flow aus der �bung.

Projekt klonen:
```git clone https://github.com/andkopp/andkopp.github.io.git```

Inhalt der Datei in einem neuen Branch �ndern:
1. Neuen Feature-Branch erstellen: ```git branch featureX_title```
2. Auf lokalem Rechner in diesen Branch wechseln: ```git checkout featureX_title```
3. Dateien erstellen oder �ndern
4. Ge�ndertere Dateien vormerken/stagen: ```git add dateiname```
5. �nderungen commiten: ```git commit -m "Commit-Nachricht"```
6. �nderungen pushen: ```git push``` bzw. ```git push --set-upstream origin featureX_title```

Anschlie�end auf github:
1. Pull Request erstellen und �ber ```#``` den Issue referenzieren.
2. Pull Request mergen und Feature-Branch l�schen.

Anschlie�end lokal:
1. Auf Master-Branch wechseln: ```git checkout master```
2. Feature-Branch auch lokal l�schen: ```git branch -d featureX_title```
3. Lokales Repository aus remote (github) aktualisieren: ```git pull```
