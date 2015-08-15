### Introduction ###
If you are using Prototype.js in your site, you could get a problem to use ezStats as a plugin, because Prototype gets into a conflict with jQuery.js, which ezStats uses.
But this conflict can easiliy be solved:


### Solution ###

  * Create a noconflict.js file and include the following code in it:
```
jQuery.noConflict();
var $j = jQuery;
```
  * Include the js files in the same order as shown below
```
<script src=”js/prototype.js” type=”text/javascript”></script>
<script src=”http://code.jquery.com/jquery-latest.pack.js” type=”text/javascript”></script>
<script src=”js/noconflict.js” type=”text/javascript”></script>
```

### Source ###
http://www.achari.in/resolve-conflict-between-jquery-js-and-prototype-js