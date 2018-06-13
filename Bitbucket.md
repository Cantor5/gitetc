Bitbucket
=========

Links to markdown files in nested directories
---------------------------------------------

I found that, it also simple to create the structure as you go along by doing the following:

1. add something like `a list of [[Wiki/Notes.md|notes]]`
2. add `== Table of contents ==`
3. and add `<<toc Wiki/ >>` to generate the automatic table.
You have to use Creole markup for this to work.

When you now save and click on the link, you have a option to create the file automatically.

To get from the Readme.md file to the wiki use something like:

~~~~
documented in the [Wiki](../../wiki/Home)
~~~~
and to get from the wiki to the repository:

~~~~
The files are all in the [[../src/|repository]].
~~~~
