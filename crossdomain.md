### What is the problem? ###

If you have ezStats installed in a different domain, or subdomain, than your CMS, the "detail-popup" does not work. Due to a security policy on the server where ezStats is installed , it blocks the request from the foreign server.

_Wenn du ezStats in einer anderen Domain, oder Subdomain, installiert hast als dein CMS, funktioniert das Detail-Popup nicht. Aufrgrund einer Sicherheitsrichtlinie blockt der Server wo ezStats installiert ist, die Anfrage vom fremden Server ab._

---


### Solution #1 ###
Make sure that ezStats is installed under the same subdomain as your CMS. If the URL of your page is `http://www.yoursite.com/`, and the URL of ezStats is `http://stats.yoursite.com/`, the detail popup do not work.<br>
Jump in the admin panel of ezStats, open the menu "Plugins" and then change the URL, so ezStats has the same subdomain as your CMS: f.e. <code>http://www.yoursite.com/folder/ezStats2/</code>.<br>
Attention: <code>http://yoursite.com</code> and <code>http://www.yoursite.com</code> are also different subdomains!<br>
<br>
<i>Stelle sicher daß ezStats unter der gleichen Subdomain wie dein CMS installiert ist. Wenn die URL deiner Seite <code>http://www.yoursite.com/</code> lautet, und die von ezStats <code>http://stats.yoursite.com/</code>, wird das Detail-PopUp nicht funktionieren.</i><br>
<i>Öffne im Adminpanel von ezStats das Menü "Plugins" und ändere dort die URL, damit ezStats die gleiche Subdomain wie dein CMS hat, zum Beispiel: <code>http://www.yoursite.com/folder/ezStats2/</code>.</i><br>
<i>Achtung: <code>http://yoursite.com</code> und <code>http://www.yoursite.com</code> sind auch unterschiedliche Subdomains!</i>
<hr />

<h3>Solution #2</h3>
Download <a href='http://gfx.ezstats.org/htaccess.zip'>these zip file</a> and extract it. You must then upload the file ".htaccess" that you just unpacked to your ezStats-folder.<br>
<br>
<i>Lade dir</i><a href='http://gfx.ezstats.org/htaccess.zip'>diese Zip-Datei</a> runter und entpacke sie. Die Datei ".htaccess" die du entpackt hast, lädst du dann in das ezStats-Verzeichnis hoch.<i><br>
<hr /></i>

<h3>Solution #3</h3>
This discontent can be solved with a simple XML file called "crossdomain.xml", which shall be taken in the root directory of the server where ezStats is installed.<br>
The code for the file you'll find below.<br>
<br>
The XML file contains a white list. Who shows up here, may access. The commented-out part with the item <code>allow-access-from</code> opens this door to all or specific domains. The asterisk (<code>*</code>) in domain and port is a wild card, thus allowing everyone access. It is better if you fill in <code>domain=""</code> the domain of your CMS.<br>
<br>
<i>Diesem Missmut lässt sich in der Regel mit einer simplen XML Datei namens "crossdomain.xml" abhelfen, die im root-Verzeichnis des Servers abzulegen ist, wo ezStats installiert ist.<br>
Den Code für die Datei findest weiter unten.</i>

<i>Die XML Datei enthält eine Whitelist. Wer hier auftaucht, darf zugreifen. Der auskommentierte Teil mit dem Element <code>allow-access-from</code> öffnet dabei Tür und Tor für spezielle oder alle Domains. Der Stern (<code>*</code>) in domain und port ist eine Wildcard und erlaubt somit jeden Zugriff. Besser ist es, wenn du unter <code>domain=""</code> die Domain deines CMS eingibst.</i>

<pre><code>&lt;?xml version="1.0"?&gt;<br>
&lt;!DOCTYPE cross-domain-policy SYSTEM <br>
    "http://www.macromedia.com/xml/dtds/cross-domain-policy.dtd"&gt;<br>
&lt;cross-domain-policy&gt;<br>
&lt;!--<br>
   &lt;allow-access-from domain="*" to-ports="*" /&gt;<br>
--&gt;<br>
&lt;/cross-domain-policy&gt;<br>
</code></pre>
<hr />