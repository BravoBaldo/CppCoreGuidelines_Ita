# CppCoreGuidelines_Ita
Italian translation of CppCoreGuidelines.
Traduzione italiana delle CppCoreGuidelines.

## HTML version formatted for browsing in Italian:

1) execute: pandoc -s -o output.html -f markdown -t html ..\\CppCoreGuidelines.md
2) Insert the body content of "output.html" (without tags &lt;body&gt; and &lt;/body&gt;) and replace the tag &lt;InsertOrgBodyHere/&gt; in a coy of the file "Shell.html"
3) Copy the first 2 lists of #S-abstract and "Supporting sections" (from &lt;ul&gt;...&lt;/ul&gt; without tags) in a new temporary text document.
	3a) replace '&lt;li&gt;&lt;a href="' with '&lt;a class="sidebar-nav-item active" href="'
	3b) remove all '&lt;/li&gt;'
	3c) insert '&lt;br/&gt;' between the 2 lists
	3d) move all the text replacing tag &lt;InsertSideBarHere/&gt; in "Shell.html"
4) Save this modified "Shell.html" as "CppCoreGuidelines_Ita.md" and Enjoy :)

## Tools used:

* [OmegaT v.5.7.1](https://omegat.org) - (but with [Okapi Filter: okapiFiltersForOmegaT-1.9-1.41.0](https://okapiframework.org/wiki/index.php/Okapi_Filters_Plugin_for_OmegaT)).
* [Pandoc v.3.1.8](https://pandoc.org).
* [Notepad++ v.8.6](https://notepad-plus-plus.org).
* [Dillinger](https://dillinger.io) - an online Markdown editor/viewer.
* [Balabolka](http://balabolka.site) - Text To Speech system

## Done

* Italian translation of [CppCoreGuidelines](https://github.com/isocpp/CppCoreGuidelines).

## ToDo

* Translation maintenance.
* [Automatic] Conversion to SQL format (database).
* Tool (app?) for read/modify CppCoreGuidelines.
* ...
