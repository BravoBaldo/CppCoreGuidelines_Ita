# CppCoreGuidelines_Ita
Italian translation of CppCoreGuidelines and some handling tool


## HTML version formatted for browsing in Italian:

1) execute: pandoc -s -o output.html -f markdown -t html ..\\CppCoreGuidelines.md
2) Insert the body content of "output.html" (without tags <body> and </body>) and replace the tag <InsertOrgBodyHere/> in a coy of the file "Shell.html"
3) Copy the first 2 lists of #S-abstract and "Supporting sections" (from <ul>...</ul> without tags) in a new temporary text document.
	3a) replace '<li><a href="' with '<a class="sidebar-nav-item active" href="'
	3b) remove all '</li>'
	3c) insert '<br/>' between the 2 lists
	3d) move all the text replacing tag <InsertSideBarHere/> in "Shell.html"
4) Save this modified "Shell.html" as "CppCoreGuidelines_Ita.md" and Enjoy :)

## Tools used:

* [OmegaT v.4.3.2 - (but with Okapi Filters For OmegaT -1.6-m38)](https://omegat.org).
* [Pandoc v.2.9.2](https://pandoc.org).
* [Notepad++ v.7.8.2](https://notepad-plus-plus.org).
* [Dillinger](https://dillinger.io) - an online Markdown editor/viewer.
* [Balabolka](http://balabolka.site) - Text To Speech system

## Done

* Italian translation of [CppCoreGuidelines](https://github.com/isocpp/CppCoreGuidelines).

## ToDo

* Translation maintenance.
* [Automatic] Conversion to SQL format (database).
* Tool (app?) for read/modify CppCoreGuidelines.
* ...
