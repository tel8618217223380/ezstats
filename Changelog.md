## Important notice ##
You have to run the installer after uploading the new version, because of changes in the database. Do not be afraid, you must not re-enter any data. Please update all players after that to avoid failures.

## v0.91 to 1.0 ##
  * Support of the Endgame-DLC for Battlefield 3
  * New Default-Theme
  * Better adaptation to dark themes
  * New Wallpaper "Air Superiority"

## v0.90 to 0.91 ##
  * Style functionality now with custom header banner

## v0.88 to 0.90 ##
  * Added new premium assignments
  * Revised style functionality

## v0.87 to 0.88 ##
Added support of Aftermath DLC:
  * Added ten new assignments
  * Added five new premium assignments
  * Added three new vehicles
  * Added two new weapons
  * Added many new ribbons and medals

## v0.86 to 0.87 ##
  * New language: Slowenian
  * Revised languages: French, Portoguese, Spanish


## v0.85 to 0.86 ##
  * Added the vehicles from Armored-Kill-DLC to the compare menu
  * Added the vehicles from Armored-Kill-DLC to the history of each player
  * Added the new premium assignments from Oct 01th
  * Improved the e107 plugin. Please reinstall it, if you already use the old e107 plugin.

## v0.84 to 0.85 ##
  * Weapons Tab: Workaround for a change in the stats-API: The knife and the AT launchers again don't count for the top-list and the weapon progress anymore
  * A new plugin method for MyBB

## v0.83 to 0.84 ##
Added support of Armored Kill DLC:
  * Added five new assignments
  * Added six new vehicles
  * Added two new vehicle categories

## v0.82 to 0.83 ##
  * Fixed an Javascript error. Now the detail-page opens correct again
  * Added five new Premium assignments
  * Added three new medals and ribbons

## v0.81 to 0.82 ##
**Assignments:**
  * The five new premium Assignments are now displayed correctly

**Platoon Sync:**
  * You can syncronize the leaderboard with platoons and set, that players are removed from the leaderboard, if they are not in the platoon anymore. It could happen that all the players were deleted from the leaderboard when Battlelog was unavailable. This bug was fixed.

**Signatures:**
  * =TFS= PapaRenner has created a pattern pack, with which you can modify the background of your signatures. You can download the pack here: http://code.google.com/p/ezstats/downloads/detail?name=signature_pattern_pack.zip
  * The signature images should no longer be cached by the browser. Now, always the actual version of the signature should be displayed.
  * A great new signature is available with the favorite weapons and vehicles. The signature was proposed by G-MAN-GUK. Don't forget to update the signatures after installing the new version of ezStats.

## v0.80 to 0.81 ##
**History charts:**
  * You can now set the time range for which the stats chart is generated. Upon opening of the history of the maximum period is displayed.

**Signatures:**
  * In addition to the URL, the BB code and HTML code will be displayed for the signatures, which you can use to embed it.
  * If you want to generate more signatures than those three, you'll find a guide on how it works: http://code.google.com/p/ezstats/wiki/custom_signatures

## v0.71 to 0.80 ##
**New plugin for Joomla**
The previous ezStats plugin for Joomla did not work under certain circumstances, or impairs the performance of the homepage. In this version of ezStats, a second plugin for Joomla is included, which runs fast and stable, but requires the installation of the plugin "Sourcerer".

**New Feature: Signatures**
ezStats can now create signatures for each player on the leaderboard in three different sizes. The signatures are on the detail page of the players, where they are copy the URL of the pictures to add it in a forum for example.
By default, the signature feature is disabled in ezStats. You can activate it in the adminpanel under the menu option "Signatures". Please note that the signatures must be updated regularly with a cron job. More information can be found in the adminpanel.

## v0.70 to 0.71 ##
  * Added support of **Close Quarters** DLC

## v0.62 to 0.70 ##
**New feature: Stats History**

As of now, there are diagrams for each player with the progress his stats! For example, you can look how your kill-death ratio or score-per-minute has developed the last time. Or which vehicle you have played as much the last time. Or if your accuracy and the percentage of your headshots has developed the same!

The data on which the charts are based, are collected since your first ezStats installation. If you add a new player, then no data is available to create the chart. After 15 stats updates, there are enough data for the diagrams.

New in this version is the way you open the detail and history site: If you move the mouse over a player's name, then it opens a small pop-up. There you can choose you whether you want to open the detail or history page, or the Battlelog or BF3Stats page. Therefore, you can disable the "Links" column on the leaderboard. This you can do in the admin panel under "Customize".

## v0.61 to 0.62 ##
**Bugfixes:**
  * The labels of the infobubbles are displayed correct now, even if they are very long.

**CMS plugins:**
  * New: vBadvanced CMPS
  * New: XenForo 1.x

**Stats Compare:**
  * The "Compare function" now has two additional menu items: Favorites and General!
  * You can now use the compare function to show almost all the stats values ​​that exist in the leaderboard overview and in the detail view. And you can directly compare your results with those of your comrades.
  * Because all those values ​​are available on the compare function, you can reduce the count of columns in the leaderboard overview to the most important columns ​​for you. This you can do in the "Admin Panel->Customize"

## v0.60 to 0.61 ##
**Bugfixes:**
  * Under certain circumstances, the synchronization of the data with Battlelog could not pushed. This is fixed.

**Stats Compare: Global rankings**
  * In the detail view you've certainly seen it: for many values there is a "Global Ranking", that is, how good you are compared to all other registered players at bf3stats.com. Now you can use the new stats compare function to compare for your global position for " Kills with headshots" or "Revives per minute as assault" with those of your comrades on the leaderboard!

## v0.53 to 0.60 ##
**Bugfixes:**
  * The infobubbles should not flicker anymore under some circumstances

**New Language:**
  * Greek (Translated by Grammatopoulos "GreatApo" Apostolos)

**New Feature: Stats-Compare**
  * With the new stats compare function, you can compare the stats of each weapon and vehicle you've played with those of your comrades in the leaderboard. You can sort by any value, to find out the best headshoter for example!
  * You can deaktivate the function here: Adminpanel->Settings. This may be neccessary, if you use ezStats as a widget f.e.

**New CMS-Plugin:**
  * Drupal

**Misc:**
  * There is now a Donation button in the login page of the adminpanel. If you like ezStats, please feel free to donate.

## v0.52 to 0.53 ##
**Last seen online:**

There is a new column in the leaderboard, which you can activate in Adminpanel->Customize: The last time a player was online. If you hover over the date, a bubble shows the name of the server the player has seen. If you click onto the date, you'll forwarded to the server infopage at BF3Stats. You'll find the Last-Seen-Online-Info in the detail page of every player as well.
The data is generated by BF3Stats, not by Battlelog. Therefor the data is not everytime as actual as the stats data!

**Platoon-Sync:**

You'll find more informations about Platoon-Sync, the new feature of ezStats since the last version, on this Wiki-page: http://code.google.com/p/ezstats/wiki/platoon_sync

**New CMS-Plugins:**
  * Clansphere
  * phpFox

## v0.51 to 0.52 ##
**Bugfixes Platoon-Sync:**
  * Platoon Sync now also works with PS3 and XBOX-platoon
  * Platoon Sync now also accepts players with spaces in name
  * Deleted players from a platoon will no longer appear on the leaderboard

**Detail-view:**
  * In the weapons tab you can now filter the weapons by kit affiliation. There is also a progress bar, how many of the primary weapons have been awarded with a service star.

## v0.50 to 0.51 ##
**Bugfixes:**
  * Enhanced compatibility to various JS-libraries

**New CMS-Plugins:**
  * wBB3
  * ocPortal 7.x
  * Joomla 2.5

**New Feature: Platoon-Sync**

In this version, you can syncronize the players in your leaderboard with those in your platoon(s). If you use this function, you've just maintain your platoons, and not in ezStats also. There are three choices: Disabled, Enabled with deletion (players will be deleted, if they are not in the platoons anymore), Enabled without deletion (players will stay in the leaderboard, even if they not in the platoons anymore)

It may be that during the first synchronization many players have to be added at to the leaderboard. Then it may be that the maximum time is exceeded, and stops the script. This is not a problem: at the next synchronization is will resume where the script has terminated.

## v0.44 to 0.50 ##
**New Features:**
  * Multiple Admins: In this version, you can add more admin accounts in the adminpanel, so mates can help you manage your leaderboard. You can grant them full access (as you have), or limited access (the can only manage players).
  * Self-Adding User: Also in this version, player can add themselves to the leaderboard. This option is disabled by default, but can be activated in Adminpanel->Settings. There are three choices: Disabled, Enabled with link (then a link to the adding-page appears in the leaderboard), Enabled without link (if you don't won't a link, you can tell your mates the URL in another way)

**Language:**
  * Czech language support

**New CMS-Plugins:**
  * phpBB Portal plugin support


## v0.43 to 0.44 ##
**New Features:**
  * In detail view are now three new tabs: Awards, Assignments and Coop!

**Bugfixes:**
  * Players should now be properly sorted by the values
  * With some server configurations the detail view did not work. This is fixed

**Language:**
  * New: Hebrew (Translated by Boaz Shako)


## v0.42 to 0.43 ##
**New Features:**
  * In detail view are now global ranks for many stats values, for weapons, vehicles and vehicles
  * In the detail view are now the equiment stats

**New CMS-Plugins:**
  * vBulletin CMS
  * Nuked Klan

**Language:**
  * New: Spanish (Translated by Teobaldo Vasquez Pina)

## v0.41 to 0.42 ##
**New Feature: Vehicle overview**
  * In detail view there is now the vehicle overview. All information about the vehicles are displayed in a fully sortable table. Detailed information on each value are shown as a mouse-over effect. Moreover, the stats of the vehicle categories are displayed as well, including the common unlocks.


**New CMS-Plugins:**
  * PHPKIT 1.6.1
  * MyBB 1.6


**Bugfixes:**
  * Fixed several bugs that could occur when a player reaches the last rank
  * B2K weapons are now in the weapons overview
  * If a weapon has no unlocks, no wrong value appears anymore
  * Detail view is now displayed correctly even with small monitors
  * During installation, the leaderboard gets a unique key assigned. With it, he can add new players to BF3Stats, and can push their updates. If the server of BF3Stats is overloaded, the leaderboard does not receive a key and the player update is faulty. From now ezStats recognizes the missing key and tries to request a key on every update

## v0.40 to 0.41 ##
**CMS-Plugins:**
  * New: Simple Machines Forum (SMF)


**Bugfixes:**
  * In plugin mode, the font-family should now inherit correctly
  * Various improvements in the CSS code of the detail views
  * If ezStats runs as a plugin for a CMS, the detail view you should now be displayed even if ezStats is installed in a different domain than the CMS


**New Feature: Weapons overview**
  * In detail view there is now the weapons overview. All information about the weapons are displayed in a fully sortable table. Detailed information on each value are shown as a mouse-over effect. Moreover, the best weapons in four categories are highlighted.

## v0.30 to 0.40 ##
**New Feature: Detail-View**
  * If you click on the leaderboard on a player's name, now a lightbox appears with detailed information of that player. It is currently limited to the Kit-, Team- and Combatstats. The interesting details such as weapons- and vehiclestats come in the next version.


**Languages:**
  * New: Norwegian (Translated by Martin Stranden)
  * Revised: French and Dutch (Adminpanel now translated)

**Bugfixes:**
  * Fixed a bug that various special characters were not displayed correctly on some servers. (Especially korean and french)


## v0.20 to 0.30 ##
**New Feature: Customizable design**
  * In admin panel you now have a new menu item: "Style". In this menu you can easily make changes to the design of your leaderboard, and customize it to your wishes!

**New Languages:**
  * Polish: (Translated by Artur "cyrq" Kubicki)
  * Dutch: (Translated by Martin "Bollesmurf" )

**Bugfixes:**
  * The compatibility with various javascript libraries was increased


## v0.15 to 0.20 ##
**New Feature: CMS-Plugins**
  * The following CMS are supported so far: DZCP, e107, ECP, Ilch, Joomla, PHPFusion, PHPKit, PHPNuke, Webspell, Wordpress
  * See also: http://code.google.com/p/ezstats/wiki/cms_plugins

**New Languages:**
  * Turkish (Translated by Fatih "MrkiLLerMan88" Es)
  * Italian (Translated by Pietro "Skar3" Mingo)
  * Korean (Translated by Son "Kananbis" JiHoon)
  * French (Translated by Adrien "DriiDrii74" Manzon)

**Bugfixes:**
  * Rank & Progress icons are now displayed correctly in any size
  * The sorting of the leaderboard is now correct when "position" is displayed in column 1



## v0.14 to 0.15 ##
**New Languages:**
  * Portuguese (Translated by Emanuel "Bejecas" Rua)
  * Russian (Translated by Vladimir "59RU" Motor59)

**Admin Panel:**
  * Update status "Error" is now more comprehensive
  * Added link back to Leaderboard

**Stats new columns:**
  * Rankicon & Progress (combined)
  * Position on the leaderboard
  * Favorite Kit & Vehicle category with Icon
  * Skill

**Bugfix:**
  * Sorting of Medals and Ribbons now works correctly
  * The sort arrows no longer overlap with the column name


## v0.13 to v0.14 ##

**New Feature: Auto-update**
  * ezStats can now not only compare the stats with the database of bf3stats.com, but also register new players at bf3stats.com. And ezStats can request bf3stats.com, syncronize the data of a player with EA's servers. For more information: http://code.google.com/p/ezstats/wiki/how_ezstats_get_the_stats

**Bugfixes:**
  * Fixed a bug where the style sheet has not been shown properly (Times New Roman-bug)
  * Fixed special character bug in German language files

## v0.12 to v0.13 ##

**New stats columns:**
  * Number of different Ribbons and Medals
  * Favored weapons, vehicles, vehicle categories, equipment
  * Rank-progress

**Other changes:**
  * The installer checks now whether the server has been disabled important functions
  * The line on the leaderboard, in which the cursor is, is highlighted now
  * A space can now be placed at the end of a clan tag
  * Battlelog and bf3stats be opened in new tab

**Bugfix:**
  * The "growing" of the leaderboard should work better now

## v0.11 to v0.12 ##

**Bugfixes**
  * Fixed a error which could occur on webspaces with PHP 5.3.x

**New Features**
  * The leaderboard has a default width of 1000 pixels. If your activated columns need more space than those pixels, the leaderboard grows automatically.
  * A "infobubble" has been added. This tooltip shows detailed infos of the value, your mouse is hovering

**Additional Changes**
  * The clantag isn't wrapped with brackets anymore.


## v0.1 to v0.11 ##

**Bugfixes**
  * Assigned nicknames are now displayed correctly
  * Error during installation in some circumstances is fixed now (Undefined variable: sql in install/index.php on line 202)

**New Features**
  * Link to Battlelog added