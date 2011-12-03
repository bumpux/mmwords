##Look what I can do

Apart from the excellent [standard Markdown] [1] stuff ...

I can change two hyphens into an em dash--on the fly. This sentence ends with a real ellipsis, although I only typed three dots ...

Copyright (c), Trademark (tm), Registered (r) are no problem.

^^this text is superscripted^^ -- but this is not.

,,this text is subscripted,, -- but this is not.

~~this text is struck out~~ -- but this is not.

->look, I am right-aligned

->and I am center-aligned<-

Here is an image:
![alt text][2]

Naturally you can include any [UTF-8 symbols][3] you like. But you can also use other symbols that may or may not always render on every device/OS, things like ⌘ ⏎ ⇧ ⌥ (unicode). If the character you like is not in UTF-8, try searching for [Unicode characters][4]. See the bottom of this file for a bunch of samples.

The small **GUI toolbar in WMD** is useful too. It eases the pain of working in a browser textarea rather than a real editor by giving you buttons for indentation where a tab key wouldn't work. Also very nice is the insert link button on the toolbar, which makes adding Markdown links really simple. It reindexes the links each time you add one and lists them at the bottom. Very clean and nice. Now if it would only handle the footnotes in PHP Markdown Extra...

##Form Inputs

### Text fields

  Frog = ___

### Radio buttons

  sex = (x) male () female

### Check boxes

  phones = [] Android [x] iPhone [x] Blackberry

### Drop down

  city = {BOS, SFO, (NYC)}

Required fields

  zip code* = ___

All this builds on and extends the [original syntax of Markdown][5]. It does not render some of the things--tables, fenced code blocks, footnotes, etc--that [PHP Markdown Extra][6] does (the Markdown version used by [Stacey][7]).

---

#  Unicode Characters (UTF-8 and beyond)

Unicode does define some other characters which are sort of Mac-specific.

⌘ - &#x2318; - &#8984; - the Command Key symbol
⌥ - &#x2325; - &#8997; - the Option Key symbol
⇧ - &#x21E7; - &#8679; - the Shift Key (really just an outline up-arrow, not Mac-specific)
⎋ - &#x238B; - &#9099; - the Escape Key ?? Power??

⇥ - &#x21E5; - &#8677; - the Tab Key symbol
⏎ - &#x23CE; - &#9166; - the Return Key symbol
⌫ - &#x232B; - &#9003; - the Delete Key symbol
⌽ - &#x233D; - &#9021; - a possible substitute for the Power symbol

⌽ - looks like the IEC 5010 power symbol 

(␛) - &#x241B; 

alternate Option btn: ⎇

alternate Tab: ⌦

Control: ⌃

⌦ is achieved by "fn ⌫" ☺ 

It's also interesting that Apple uses 

↖ for Home 
↘ for End 
⇞ for Page Up 
⇟ for Page Down 
⌤ for Enter (even though its use is not consistent app to app) 
⇪  - CAPS LOCK would be unicode U+21EA, &#x21EA; &#8682; 

[Extracted from here][8]. Gory details and some peeves. Sum: these seem widespread enough to use without worry now.

---


  [1]: !http://daringfireball.net/projects/markdown/syntax "New window URL. Notice that this URL in Markdown begins with an exclamation! mark. This makes it open in a new window."
  [2]: http://ts2.mm.bing.net/images/thumbnail.aspx?q=1056153471193&id=4318dee94cc91143c6513cde086de7a7&url=http%3a%2f%2fwww.clker.com%2fcliparts%2fF%2fB%2fy%2fZ%2f1%2ft%2fadsf-hi.png "hover!"
  [3]: http://utf8-characters.com/search/ "Search for UTF-8 characters"
  [4]: http://www.fileformat.info/info/unicode/char/search.htm
  [5]: !http://daringfireball.net/projects/markdown/syntax "New window URL. Notice that this URL in Markdown begins with an exclamation! mark. This makes it open in a new window."
  [6]: http://michelf.com/projects/php-markdown/extra/ "PHP Markdown Extra"
  [7]: http://staceyapp.com/documentation/creating-pages/editing-content/ "Editing Content in Stacey"
  [8]: http://hea-www.harvard.edu/~fine/OSX/unicode_apple_logo.html

