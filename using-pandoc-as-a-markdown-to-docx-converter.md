Using Pandoc as a Markdown to Docx converter

So, I don't really like Word. But it's nearly unavoidable, 
especially in office environment (see what I did here?).

Word has some good things, it can be read and edited by most
people and can be easily converted to Kindle format. 

So the command line:

    pandoc -o output.docx -f markdown -t docx input.md

Tadah! And if you are in Windows right now, one good thing is
that you can run pandoc without installing - doesn't require being
admin! [Also I've made a `.bat` for making this easier in Windows](
https://gist.github.com/ericoporto/ccf9547d9e4d0786113c). The bat
in action below: 

![drag and drop](https://cloud.githubusercontent.com/assets/2244442/13187576/16cd68bc-d733-11e5-8629-802042f7bda6.gif)

If you need help writing markdown, [here is a cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)!

Tags: command-line-tools
