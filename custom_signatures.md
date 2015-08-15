## Introduction ##

ezStats offers three different signatures for each player, which yo can adjust slightly. But perhaps you like only "med"-signature, but want two or more of them with different background images. This article explains, how you can realize this by some modifications of ezStats.

The program I use for editing of the source code is [Notepad++](http://notepad-plus-plus.org/). This manual works with ezStats version 0.81 or higher

## Details ##

Download the file `tmp/defaults.js` and open it in Notepad++. Scroll down to the end of the file, and copy the entries of the signature you want to duplicate. In this case `med`.
» [Picture 1](http://gfx.ezstats.org/sig01.png)

Now paste the code after `"min_background_offset": "0"`. Change the prefix of the duplicated lines into "custom1" for example. And change the value of the signature type into "custom1". Please be sure that all lines end with a comma, exept the last one.
» [Picture 2](http://gfx.ezstats.org/sig02.png)

Now save the file and upload it. Then download the file `classes/signatures.php` and open it in Notepad++. In line 9, append the prefix "custom1" to the array.
» [Picture 3](http://gfx.ezstats.org/sig03.png)

Search now for the string `function create_rankicon`. The search function opens with "CTRL+F". Now paste the code `OR $type == "custom1"` in the If-loop of "med" for this example.
» [Picture 4](http://gfx.ezstats.org/sig04.png)

Then search for the string `function create_text`. To increase clarity, click on the boxes with the minus, on the left side of the If-loops. The lines inside the loops are hidden now.
» [Picture 5](http://gfx.ezstats.org/sig05.png)

Now paste paste again the code `OR $type == "custom1"` in the If-loop of "med" for this example.
» [Picture 6](http://gfx.ezstats.org/sig06.png)

Now save the file and upload it. Then download the file `admin/templates/signatures.html` and open it in Notepad++. Scroll to the bottom, duplicate the h2- and ul-code and rename "med" with "custom1".
» [Picture 7](http://gfx.ezstats.org/sig07.png)

Now save the file and upload it. Then download the latest version of ezStats. Extract the folder "install" in it, and upload it too. Open the installer with your browser, and click through all steps. Afterwards, you'll find your new signatures in the adminpanel of ezStats!