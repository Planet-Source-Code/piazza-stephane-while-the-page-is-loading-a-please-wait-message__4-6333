<div align="center">

## While the page is loading, a PLEASE WAIT message


</div>

### Description

Add those lines at the beginning of your page if there is a lot of pictures aso.

While loading, a message will appear and will be hidden when the page will be fully loaded.

Enjoy it ... And if u like it .... rate it ....

Let's go to www.editeurjavascript.com to find a lot of javascript programs as this one.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[PIAZZA Stephane](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/piazza-stephane.md)
**Level**          |Beginner
**User Rating**    |4.8 (87 globes from 18 users)
**Compatibility**  |HTML
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__4-33.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/piazza-stephane-while-the-page-is-loading-a-please-wait-message__4-6333/archive/master.zip)





### Source Code

```
<BODY onLoad="cacheOff()">
<!-- BEGINNING OF THE SCRIPT -->
<STYLE TYPE="text/css">
<!--
#cache {
 position:absolute; left=10; top:10px; z-index:10; visibility:hidden;
}
-->
</STYLE>
<!--
Lines above are creating a layer which show a message
displaying the 'PLEASE WAIT ... ' message
-->
<SCRIPT LANGUAGE="JavaScript">
ver = navigator.appVersion.substring(0,1)
if (ver >= 4)
	{
	document.write('<DIV ID="cache"><TABLE WIDTH=400 BGCOLOR=#000000 BORDER=0 CELLPADDING=2 CELLSPACING=0><TR><TD ALIGN=center VALIGN=middle><TABLE WIDTH=100% BGCOLOR=#FFFFFF BORDER=0 CELLPADDING=0 CELLSPACING=0><TR><TD ALIGN=center VALIGN=middle><FONT FACE="Arial, Verdana" SIZE=4><B><BR>PLEASE WAIT ... <BR><BR></B></FONT></TD> </TR></TABLE></TD> </TR></TABLE></DIV>');
	var navi = (navigator.appName == "Netscape" && parseInt(navigator.appVersion) >= 4);
	var HIDDEN = (navi) ? 'hide' : 'hidden';
	var VISIBLE = (navi) ? 'show' : 'visible';
	var cache = (navi) ? document.cache : document.all.cache.style;
	largeur = screen.width;
	cache.left = Math.round(100);
	cache.visibility = VISIBLE;
	}
function cacheOff()
	{
	if (ver >= 4)
		{
		cache.visibility = HIDDEN;
		}
	}
</SCRIPT>
<!--
When the page will be fully loaded, the message will be hidden
-->
```

