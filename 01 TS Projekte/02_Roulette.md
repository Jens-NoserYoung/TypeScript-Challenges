# 🎲 Projekt Roulette 
In diesem Projekt geht es darum eine vereinfachte Version des Casino Spiels Roulette zu bauen. Es soll einen vereinfachten
Roulettetisch zu verfügung stehen, auf welchem man seine wetten Platzieren kann. Sobald mann mit dem setzen fertig ist,
klickt mann auf Roll. Nun soll eine kleine Animation angezeit werden um die Gewinnnummer anzuzeigen. Sobald die Gewinnummer
bekannt ist, soll berechnet werden, ob und wenn ja wie viel der Spieler in dieser Runde gewonnen hat. Zum Schluss wird das
Resultat dem User angezeigt und er kann eine weitere Runde am Roulette Tisch gamblen. Im unten verlinkten Video siehst 
du ein mögliches Beispiel.

⏳ 9 Tage

[![Beispiel](../02%20Ressourcen/02%20Roulette/cover.jpg)](../02%20Ressourcen/02%20Roulette/beispiel.mov)

---

## ☑️ Anforderungen
- Der Roulettetisch enthält alle Felder welche im Video gezeigt werden
- Die Gewinnnummer wird mithilfe der getRandomNumbersApi bestimmt
- Die Gewinnnummer wird mit einer Animation angezeigt
- Der eingesetzte Betrag sowie das Resultat der jeweiligen Runde ist für den Benutzer ersichtlich
- Die Applikation funktioniert auch wenn die API nicht mehr erreichbar is
- Das Projekt ist im Ordern 03 Abgabe / 02 Roulette abgelegt

### getRandomNumbersApi
- URL: https://www.randomnumberapi.com/

## 📖 Regeln
1. Wenn eine Zahl getroffen wird erhählt der Benutzer das 36 Fache des Einsatzes als Gewinn
1. Wenn eine 1/3 Option (1st, 2nd, 3rd) getroffen wird erhält er das dreifache des als Gewinn
1. Wenn eine 1/2 Option (1-18, Even, Red, Black, Odd, 19-36) getroffen wird erhält er das doppelte
 des Einsatzes als Gewinn
