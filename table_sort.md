_Deutsche Version weiter unten_

### Introduction ###

By default, the leaderboard is sorted after the first table column, which is typically rank or position.
The sorting can be changed by clicking on the table header of the desired column. Another click on it changes the sort direction.

If you want to change the default sorting, you can do this through a relatively simple change.

### Details ###
  * If you have a ezStats version up to 0.15, open the file `templates/_index.html` with a text editor. If your version is 0.20 or higher, open the file `templates/plugin.html` or `templates/standalone.html`. Depending on which mode you are using ezStats.
  * Search for the text fragment `sortList`.
  * If you want to sort by the fourth column of the leaderboard, in ascending order, then change the row into this: `sortList: [[3,0]],`
  * If you want to sort by the first column of the leaderboard, in descending order, then change the row into this: `sortList: [[0,1]],`
  * If you want to sort by the eighth column of the leaderboard, in descending order, then change the row into this: `sortList: [[7,1]],`
  * ... and so on.


---


### Einführung ###

Standardmäßig wird die Leaderboard-Tabelle nach der ersten Spalte sortiert, was in der Regel der Rang oder die Position ist.
Die Sortierung kann geändert werden, indem man auf den Tabellenkopf der gewünschten Spalte klickt. Ein weiterer Klick darauf ändert die Sortierrichtung.

Wenn du die Standard-Sortierung ändern möchtest, kannst du dies durch einen relative simple Änderung machen.

### Details ###
  * Wenn du eine ezStats-Versionen bis 0.15 nutzt, öffne die Datei `templates/_index.html` mit einem Texteditor. Wenn deine Version 0.20 oder höher ist, öffne die Datei `templates/plugin.html` oder `templates/standalone.html`. Je nachdem welchen Modus von ezStats du verwendest.
  * Suche nach dem Textfragment `sortList`.
  * Wenn du nach der vierten Spalte im Leaderboard, aufsteigend sortieren willst, dann ändere diese Zeile wie folgt: `sortList: [[3,0]],`
  * Wenn du nach der ersten Spalte im Leaderboard, absteigend sortieren willst, dann ändere diese Zeile wie folgt: `sortList: [[0,1]],`
  * Wenn du nach der achten Spalte im Leaderboard, absteigend sortieren willst, dann ändere diese Zeile wie folgt: `sortList: [[7,1]],`
  * ... und so weiter.