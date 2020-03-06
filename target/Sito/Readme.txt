http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines

Internet Explorer (NO Chrome)
HTML
Select All
Copy
Paste in a new text
Change path of "stylesheet"s (prepend a dot)
Si veda anche: F:\Dati\OmegaT\Pandoc

1) pandoc -s -o output.html -f markdown -t html    ..\CppCoreGuidelines.md
2) Insert the body content of "output.html" (without tags <body> and </body>) replacing the tag <InsertOrgBodyHere/> in the file "Shell.html"
3) Copy the first 2 lists of #S-abstract and "Supporting sections" (from <ul>...</ul> without tags) in a new temporary doc.
	3a) replace '<li><a href="' with '<a class="sidebar-nav-item active" href="'
	3b) remove all '</li>'
	3c) insert '<br/>' between the 2 lists
	3d) move all replacing tag <InsertSideBarHere/> in "Shell.html"