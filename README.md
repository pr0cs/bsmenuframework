# bsmenuframework
** March 5, 2019 **

A fork of the design from: https://bootsnipp.com/snippets/prnvG

I wanted a darker menu system with some reasonable animation.  There are a lot of bootstrap menus out there but they're all kinda boring and/or have been languishing for so long that the version of bootstrap, jquery that were used along with the messy css and js content made fixing them more work than developing something from scratch.

My purpose in revising some of the original design from bootsnipp was that I wanted to adapt the menu system for something more involved like tying it to thymeleaf for a project I'm piddling with.  I'm not much of a web developer, but I did manage to revise the original design to allow the developer to label <li> elements as 'expanded' which is something the original design did not do.  
  
I also had to decompress the original packed js and add the section for expanded.  The JS is actually semi-readable now so you can at least see what it's doing, I understand the purpose of minifying shit and trying to compress it but purposely packed stuff like that is annoying and often worrying (as seen in the original bootsnipp comments suggesting virus scanning saying the original .js had a virus).  With everything uncompressed you can at least see what it does now.

Technology included:
- **jquery-3.3.1** - animation et al
- **bootstrap-4.3.1-dist** - bootstrap framework
I've kept the two releases intact, yeah it takes more disk space but there is nothing stopping you from using the .min css/js with very minor edits.

Known issues:
- colors other than the default need minor additions to the css to accomodate for the active/sub-menu elements.  They're close but I didn't add them, I was happy with the default color
- at the time I posted this it's not entirely clear how difficult it will be to actually use the menu system for a front-end of a page, my changes were just to get the menu code easier to read, more practical and cleaner
