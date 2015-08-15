_Deutsche Version weiter unten_

### Introduction ###
ezStats can syncronize the players of your leaderboard with those in your Battlelog-platoons. This has the advantage that you need only maintain your platoon, your leaderboard is then actual automatically.

### Add platoons ###
In the adminpanel of ezStats, on the menu option "player", you will find the heading "Platoon Sync".	To find out the Platoon ID, open the Platoon page in Battlelog. The URL of this page has the format: `http://battlelog.battlefield.com/bf3/platoon/1234567890123456789/`. The ID is the 19-digit number in the URL. Do not forget to select the correct platform.

### The options ###
In the drop-down menu you can choose between three modes:
  * No synchronization with platoons: Whether you have entered platoons or not, it synces not
  * Sync with platoons, players will not be deleted: You can add players to the leaderboard, even if they are in no platoon
  * Sync with platoons, players will be deleted (!): If players are not in a platoon, they are removed from the Leaderboard

You can also specify the sync-frequency, it is by default at 5. What it is all about, is in the next section.

### Syncronize ###
To syncronize the leaderboard with the platoons, run an update of the players. You find the button "Update player now!" in the "Update player" section. If you have specified the sync frequency as "5", four times the stats data of the player will be updated, and the fifth time the platoons synchronizes. I recommend to create a [cronjob](http://code.google.com/p/ezstats/wiki/update_the_stats) that will do this once every hour.

### The first synchronization ###
It may be that during the first synchronization many players have to be added at to the leaderboard. Then it may be that the maximum time is exceeded, and stops the script. This is not a problem: at the next synchronization is will resume where the script has terminated.
You can set the sync frequency to "1", then it synchronizes with every click on "Update player now!" with the platoon. But do not forget to set it to "5" or higher again!


---


### Einführung ###
ezStats kann die Spieler deines Leaderboards mit denen in deinen Battlelog-Platoons syncronisieren. Dies hat den Vorteil, daß du nur deine Platoons pflegen musst, dein Leaderboard ist dann automatisch auf dem gleichen Stand.

### Platoons hinzufügen ###
Gehe im Adminpanel von ezStats auf den Menüpunkt "Player"; dort findest du die Rubrik "Platoon Sync".
Unter "Platoonverwaltung" kannst du nun die Platoon-IDs deiner Platoons eingeben. Um die Platoon-ID herauszufinden, öffne die Platoon-Seite im Battlelog. Die URL dieser Seite hat dieses Format: `http://battlelog.battlefield.com/bf3/platoon/1234567890123456789/`. Die ID ist die 19-stellige Zahl in der URL. Vergiss nicht, die korrekte Plattform auszuwählen.

### Die Optionen ###
In dem Drop-Down-Menü kannst du zwischen drei Modi wählen:
  * Keine Synchronisation mit Platoons: Egal ob du Platoons eingetragen hast oder nicht, es wird nicht syncronisiert
  * Synchronisation mit Platoons, Spieler werden nicht gelöscht: Du kannst Spieler zum Leaderboard hinzufügen, auch wenn sie in keinem Platoon sind
  * Synchronisation mit Platoons, Spieler werden gelöscht (!): Wenn sich Spieler nicht in einem Platoon befinden, werden sie aus dem Leaderboard gelöscht

Außerdem kannst du die Syncronisations-Frequenz angeben, sie standardmäßig bei 5 liegt. Was es damit auf sich hat, steht im nächsten Abschnitt

### Syncronisieren ###
Um das Leaderboard mit den Platoons zu syncronisieren, starte ein Update der Spieler. Die Schaltfläche findest du in der Rubrik "Spieler aktualisieren". Wenn du als Syncronisations-Frequenz "5" angegeben hast, werden erst viermal die Statsdaten der Spieler aktualisiert, und beim fünften Mal die Platoons syncronisiert. Ich empfehle einen [Cronjob](http://code.google.com/p/ezstats/wiki/update_the_stats) anzulegen, der dies einmal stündlich erledigt.

### Die erste Syncronisierung ###
Wenn bei der ersten Syncronisierung viele Spieler auf einmal zum Leaderboard hinzugefügt werden, kann es sein daß die maximale Ausführungsdauer überschritten wird, und das Skript abbricht. Dies ist kein Problem: bei der nächsten Syncronisierung wird wird dort fortgesetzt, wo das Skript abgebrochen hat.
Du kannst die Syncronisations-Frequenz auf "1" stellen, dann wird bei jedem Klick auf "Spieler aktualisieren" mit den Platoons syncronisiert. Aber vergiss nicht danach wieder auf "5" oder höher zu stellen!