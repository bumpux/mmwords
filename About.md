##Mark My Words <title>Mark My Words</title>

####The poor man's [Scrivener][1] + [Marked][2]

Write text & hypertext, easy. Get clean html or PDF.

**Advantages, Gotchas, and "Interesting"**

<!--  /////////////   this is a non-previewed block of stuff

it does appear in the rendered HTML as a comment, though


use as much vertical space as you like; 





/////////////  -->


*Stop worrying, focus on writing*

 - Twin focus--input pane and preview--I can argue it square or round. I like the clean preview. But there may be a tendency to think of it like a word processor and
 try to double click / edit in the preview.
 - Add a link while without fiddling with finding/copying/pasting a URL at that moment. The URLs stay in an autonumbered list at the bottom of the page. Fill 'em in later.
 - Undo: limited Command/Ctrl+Z; be careful of page refreshes! It seems that so far, if you wipe the input but refresh, *you can restore it by going back in browser history*.
 - Fully styleable for screen and print via CSS
 - Spell-check if you want it (Chromium: right-click the input > Spell-checker Options)
 - Try this: 
   - Invoke Quicksilver. 
   - Type a period (.)
  - Type stuff, Markdown maybe
   - Tab 
   - "Put on Shelf"
   - Later, drag from the Shelf to MMW and sort it all out.
 - Email to Posterous: Put Markddown inside a `<markdown></markdown>` block. Cool.

*"File" Management

 - set the browser preference to restore previous windows on restart
 - close the app anytime and it restores work in progress automagically
 - Tabs auto-save multiple docs (testing in Chromium).
 - When you need to save something, select all in the input, and drag (to a folder, to the desktop, to the QS Shelf). This creates an OS X Text Clipping. To edit, drag the clippings back into the input pane. (*Sweet enough? Not quite. Still need a way to open a file and have it appear in a new broswer tab inside MMW.*)

*Export*

 - **Print or PDF**: Added a print style sheet. In the browser, just hit Print, Preview, Save as PDF. ***Gill Sans***, why not?
 - **HTML:** See the little box below the input field? Copy. Paste.
 - Check out [look-what-I-can-do.md][3] for the current state of features / utility. 

*Tips and/or hacks*

 - `Command+Shift+{` is your friend in a tabbed Webkit browser :-)
 - If the page gets long, grab the handle on the input box and make it bigger.
 - you could place intentionally mis-spelled words in the Markdown so that the become visible markers (poor man's syntax highlighting)
 - <!-- use html comment blocks to hide stuff from the preview -->
 - `<!-- use html comment blocks to hide stuff from the preview -->`: see previous bullet in the Markdown
 - use `<div class="markdown"> *Markdown here.* </div>` for working with Stacey/PHP Markdown Extra. See below:
 - <div class="markdown"> *Markdown here.* </div>

*Limitations*

 - no syntax highlighting in the source/input pane. May want to use external editor for longer docs

**List of things TBD:**

But seriously putting this up online is good idea for a host of reasons. Getting to know github is one.

 - ~~make <title> change dynamically to whatever the first line of Markdown is.~~ <br /> **fixed**: make first line = `## Previewed Title <title>Real HTML Title</title>` (dropped `<title>` from the html file `<head>` -- so declaring in `<body>` via Markdown works :-)
 - Nice to have a GUI like WMD that would handle the nice things about [PHP Markdown Extra][4] like tables and footnotes. Question asked here: http://stackoverflow.com/q/4166971 
*[MultiMarkdown 3][5] can do footnotes, tables, definition lists, citations*. Seems mainly focused on wide range of export options (Latex, etc) Also, Multimarkdown is a local server install. MMW uses a javascript port of showdown.js, so it's portable. Thinking we have to live without footnotes and tables in this edit mode. Stacey uses PHP markdown with the extra goodies.
 - also nice to have: selection "echo" between panes (see twin focus above)
 - [Stacey][6]-fy it for publication; have specific pages showing examples;
 - Show/hide preview pane?

 

**Credit**

This comes via a project called WMD, and a series of forks and branches based on the original release. Fascinating to follow the chain of tweaks. I'm working with [this version, aimed to include form elements in Markdown][7]. 

Shoulders of Giants:
> 
Github Dudes...
WMD project
Gruber (markdown)
HTML


  [1]: http://
  [2]: http://
  [3]: look-what-I-can-do.md
  [4]: http://michelf.com/projects/php-markdown/
  [5]: http://fletcher.github.com/peg-multimarkdown/mmd-manual.pdf
  [6]: http://staceyapp.com
  [7]: https://github.com/maleldil/wmd "Maledil's fork of WMD"
