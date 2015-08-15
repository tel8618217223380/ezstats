_deutsche Version weiter unten_


## From where gets ezStats the stats values? ##
There is no direct access to the stats-server from EA. Therefore ezStats get the stats by using the puplic API from the site http://bf3stats.com

bf3stats uses a own database and so you have no realtime access to the stats data using the API.

If you want the stats from player "shyguy", you have to log on the player on bf3stats. bf3stats searches for the player in EAs database and add him to its own.
If you want the actual stats of "shyguy", bf2stats has to synch its database with EAs one. Then you may receive receive the newest data from the API.


## How it works in detail? ##
During the installation of ezStats your leaderboard is automatically assigned an ID number and a password. So your Leaderboard entitled to register a new player at bf3stats.com and to syncronize data with EA's servers.

The comparison of ezStats' data with the data of bf3stats is unlimited. The order to register a player or to sync with EA is limited to 10 requests per hour.


## How do I set the update function of ezStats best? ##
By default, ezStats updates 15 playerss per call of the update function. You can set the value higher. When the loading icon does not disappear after the specified time, the value was too high. The number of players that ezStats can update simultaneously depends on the characteristics of your webspace.

Players who are not yet in the database of bf3stats.com, will be automatically registered by ezStats. It may take some time until the data is available.

By default, ezStats synchronizes with EA servers if the players data is older 12 hours. This setting was chosen because your leaderboard is only entitled to ten requests per hour.
If you only have a few players on the leaderboard, you can reduce the time. Do you have many players on the leaderboard, you need to set up time. If you've exhausted your limit, the player got the state "error".


## Should I use a cron job? ##
By limiting the number of requests it is even necessary. I recommend to mandate a cron job, to call the update function every hour. The URL can be found in the Admin Panel.
Free cronjobs you can create at http://www.setcronjob.com (English) or http://www.cronjob.de (German).

<br />

## Von wo erhält ezStats die Stats-Daten? ##
Es gibt keinen direkten Zugriff auf die Stats-Server von EA. Dafür gibt es die öffentliche API der Seite http://bf3stats.com.

bf3stats hat eine eigene Datenbank, und somit hat man keinen Echtzeit-Zugriff auf die Stats mit dieser API.

Wenn man z.B. die Stats des Spielers "shyguy" abrufen will, muss man diesen zuerst bei bf3stats anmelden. bf3stats sucht dann in EAs Datenbank nach ihm, und speichert ihn dann in seiner eigenen. Wenn man dann die aktuellen Stats von "shyguy" haben will, muss bf3stats die Datenbank mit EAs Datenbank synchronisieren. Dann erhält man die neuesten Daten von der API.


## Wie funktioniert das im Detail? ##
Während der Installation von ezStats bekommt euer Leaderboard automatisch eine Ident-Nummer zugewiesen, sowie ein Passwort. Mit diesen Daten ist euer Leaderboard berechtigt, bei bf3stats.com einen neuen Spieler zu registrieren und die Daten mit EAs Server zu syncronisieren.

Der Abgleich der Daten von ezStats mit den Daten von bf3stats ist unlimitiert. Der Auftrag einen Spieler zu registrieren oder mit EA zu syncen ist limitiert auf 10 Anfragen pro Stunde.


## Wie stelle ich die Update-Funktion von ezStats am Besten ein? ##
ezStats aktualisiert standardmäßig 15 Spieler pro Auruf der Update-Funktion. Du kannst den Wert höher stellen. Wenn beim Aktualisieren das Ladesymbol nicht spätestens nach der angegebenen Zeit verschwindet, war der Wert zu hoch. Die Anzahl Spieler die ezStats gleichzeitig aktualisieren kann, hängt von den Eigenschaften deines Webspace ab.

Spieler die noch nicht in der Datenbank von bf3stats.com sind, meldet ezStats automatisch dort an. Es kann etwas dauern, bis seine Daten dann zur Verfügung stehen.

Standardmäßig beauftragt ezStats eine Synchronisierung mit EAs Servern, wenn die Spielerdaten älter wie 12 Stunden sind. Diese Einstellung wurde deswegen gewählt, weil dein Leaderboard nur zu zehn solcher Anfragen pro Stunde berechtigt ist.
Wenn du nur wenige Spieler im Leaderboard hast, kannst du die Zeit reduzieren. Hast du viele Spieler im Leaderboard, musst die Zeit hochsetzen. Wenn du dein Limit ausgeschöpft hast, erkennst du das am Status "error"


## Soll ich ein Cronjob verwenden? ##
Durch die Limitierung der Anfragen ist es sogar notwendig. Ich empfehle einen Cronjob damit zu beauftragen, jede Stunde die Updatefunktion aufzurufen. Die URL findest du im Adminpanel.
Kostenlose Cronjobs kannst du bei http://www.setcronjob.com (englisch) oder http://www.cronjob.de (deutsch) anlegen.