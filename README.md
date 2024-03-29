<div style="display:flex;" align="center">
  <img alt="Logo" src="./docs/img/logo_dlds.png" width="400px" />
</div>

# Die Liga der Sterblichen
Dieses Projekt ist eine Nachbildung des Serverplugins von Robert für das Minecraft-Projekt DLDS von PietSmiet.
Das Datapack stellt die Grundlagen von DLDS so weit wie möglich nach, das sind:
- Punkte für den jeweiligen Mob
- Geänderte erst Drops der jeweiligen Mobs
- Anzeige des aktuellen Punktestands
- Anzeige über den Fortschritt
- Start mit Verteilung über die Map

Dazu kommt noch die Möglichkeit eines globalen Scoreboard welches in den Kommentaren und auch hier schon gewünscht wurde. Das Scoreboard ist optional und muss angeschaltet werden. (siehe [Übersicht der Befehle](#Übersicht-der-Befehle))

> Hinweis: Die Funktionen mussten ein wenig abgeändert werden, da Datapacks in den Funktionen limitiert sind.

# Einrichtung
1. Um DLDS spielen zu können benötigst du das DLDS-Datapack welches du [hier](https://github.com/otti-ai/dlds/releases/latest) herunterladen kannst.
2. Erstelle eine neue Welt mit folgenden Einstellungen:
- Spiel -> Cheats erlauben: An (Wird für das Starten und Anzeigen der Punkte benötigt)
- Mehr -> Datenpakete anklicken: In das neue Fenster zieht ihr via Drag-and-drop das Datapack rein und bestätigt das hinzufügen. Nun sollte das DLDS-Datapack links in der Liste angezeigt werden: ![datapack install](/docs/img/datapack1.JPG)
Nun einmal das Datenpaket anklicken. Es sollte sich jetzt auf die rechte Seite verschieben. Danach die Auswahl mit klick auf Fertig bestätigen.
3. Nachdem ihr die neue Welt erstellt habt, könnt ihr DLDS mit der Chat Eingabe `/function dlds:start` starten. Mit `/function dlds:punkte` könnt ihr euch die Punkte Anzeigen.

# Übersicht der Befehle
Jeder der folgenden Befehle kann im Chat mit `/function` gestartet werden und fängt immer mit `dlds:` an.
- `dlds:start` Mit diesem Befehl startet ihr DLDS und werdet an einem zufälligen Ort in der Welt teleportiert. (Radius 500 Blöcke um den Spawn)
- ![game start](/docs/img/start.jpg)
- `dlds:restart` Setzt die Punkte zurück.
- `dlds:punkte` Zeigt euch eueren aktuellen Punktestand an und den Fortschritt bei den Mobs
- ![points](/docs/img/punkte.jpg)
- `dlds:scoreboard` Aktiviert eine Punktetabelle am rechten Bildschirm Rand
- ![scoreboard](/docs/img/scoreboard.jpg)


