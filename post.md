[BrettTerpstra.com][1]

   [1]: https://brettterpstra.com/

  * [BrettTerpstra.com][2]
  * [projects][3]
  * [topics][4]
  * [archive][5]
  * [contribute][6]
  * [sponsor][7]
  * [about/contact][8]
  *     * [][9]
    * [][10]
    * [][11]
    * [][12]
    * [][13]

   [2]: https://brettterpstra.com/
   [3]: https://brettterpstra.com/projects/
   [4]: https://brettterpstra.com/topics/
   [5]: https://brettterpstra.com/archives/
   [6]: https://brettterpstra.com/support/
   [7]: https://brettterpstra.com/sponsorship/
   [8]: https://brettterpstra.com/contact/
   [9]: https://twitter.com/ttscoff (ttscoff on twitter)
   [10]: https://www.instagram.com/ttscoff/ (ttscoff on instagram)
   [11]: https://pinboard.in/u:ttscoff (ttscoff on pinboard)
   [12]: https://github.com/ttscoff (ttscoff on github)
   [13]: http://brett.trpstra.net/brettterpstra (subscribe)

brett terpstra archive topics projects contribute sponsor subscribe about/contact

[Work smarter and accomplish more with Pagico][14]

   [14]: https://synd.co/2mAPW5G

  * Settings
  * * * *

  * Light Mode
  * Dark Mode
  * Automatic
  * * * *

  * TL;DR
  * Links open tabs
  * SuperReadable

[« Web excursions: December 27, 2011 - January 3, 2012][15] | [Web excursions: January 4, 2012 - January 15, 2012 »][16]

   [15]: https://brettterpstra.com/2012/01/04/web-excursions-december-27-2011-january-3-2012/ (Web excursions: December 27, 2011 - January 3, 2012)
   [16]: https://brettterpstra.com/2012/01/15/web-excursions-january-4-2012-january-15-2012/ (Web excursions: January 4, 2012 - January 15, 2012)

# Scripting Readability and Markdownify for clipping web pages

Jan 4th, 2012 [[Tweet][17]]

   [17]: https://twitter.com/intent/tweet?original_referer=https%3A%2F%2Fbrettterpstra.com%2F%2F2012%2F01%2F04%2Fscripting-readability-markdownify-for-clipping-web-pages%2F&text=Scripting+Readability+and+Markdownify+for+clipping+web+pages&url=https%3A%2F%2Fbrettterpstra.com%2F%2F2012%2F01%2F04%2Fscripting-readability-markdownify-for-clipping-web-pages%2F&via=ttscoff (Tweet this post)

![read2text header image][18]

   [18]: https://brettterpstra.com/uploads/2012/01/read2textheader.jpg (read2text header)

I wanted to share a handy tool that I realized I use daily but rarely talk about. I call it Read2Text, but it’s really just a Frankenstein script which combines [Python Readability][19] ([license][20]) with [html2text][21] ([license][22]). The combination allows you to grab web pages, process them with a port of [Arc90’s Readability][23] and convert the HTML to Markdown, ready for pasting or piping to a text file.

   [19]: https://github.com/gfxmonk/python-readability/blob/master/README
   [20]: http://www.apache.org/licenses/LICENSE-2.0
   [21]: http://www.aaronsw.com/2002/html2text/
   [22]: https://github.com/aaronsw/html2text/blob/master/COPYING
   [23]: http://lab.arc90.com/2009/03/02/readability/

[nvALT][24] has this built in, but it’s been a little crashy lately. I find it more reliable to just do this from the command line. If you install it in your path (both the `read2text` script and the “readability” folder), you can run `read2text http://brettterpstra.com/keybinding-madness/ | pbcopy`.

   [24]: http://brettterpstra.com/project/nvalt/

You’ll get a Markdown-ified version of the page, with links, image links, headers, code blocks and text intact, but no comments, sidebars, ads, etc. It’s not perfect, but it does a solid job and cleanup only takes me a minute, even on huge sites. I use this most of the time instead of clipping to Evernote these days.

I alias it in my .bash_profile to `rtt`, and often redirect the output straight to a text file in my nvALT folder: `rtt http://grml.org/zsh/zsh-lovers.html > ~/Dropbox/Notes/nvALT2.1/zsh\ lovers.md`

Now I have a new note that automatically shows up in nvALT with the text of the zsh-lovers page (yeah, I tried switching to zsh this morning. I’ll have to come back to that). Anyway, I thought others might find this hack of use, so I’m making the download available below.

#### Read2Text v1

[![][25]][26]

   [25]: https://cdn3.brettterpstra.com/downloads/thumbnails/2012/01/read2texticon.png
   [26]: https://cdn3.brettterpstra.com/downloads/Read2Text1.zip (Download Read2Text v1)

[Download Read2Text v1][27]

   [27]: https://cdn3.brettterpstra.com/downloads/Read2Text1.zip

A Frankenstinian combination of html2text and Python Readability. This command line tool makes clipping web pages into Markdown text without ads and comments simple.

Published 01/04/12.

Updated 01/04/12. [Changelog][28]

   [28]: https://brettterpstra.com/2012/01/04/scripting-readability-markdownify-for-clipping-web-pages/

[Donate][29] • [More info…][30]

   [29]: https://brettterpstra.com/donate/
   [30]: http://brettterpstra.com/scripting-readability-markdownify-for-clipping-web-pages (More information on Read2Text)

By the way, I also have [a web service][31] for this. You can get [raw markdown][32] or a [nice interface][33] for previewing and copying. There’s also an API and bookmarklets for integration into your favorite browser. Have fun!

   [31]: http://markdownrules.com/
   [32]: http://fuckyeahmarkdown.com/go/?u=http%3A%2F%2Fbrettterpstra.com%2Fscripting-readability-markdownify-for-clipping-web-pages%2F&read=1
   [33]: http://fuckyeahmarkdown.com/go/?read=1&showframe=1&u=http%3A%2F%2Fbrettterpstra.com%2Fscripting-readability-markdownify-for-clipping-web-pages%2F

Your support is greatly appreciated!

[Tweet this.][34]

   [34]: https://twitter.com/intent/tweet?original_referer=https%3A%2F%2Fbrettterpstra.com%2F%2F2012%2F01%2F04%2Fscripting-readability-markdownify-for-clipping-web-pages%2F&text=Scripting+Readability+and+Markdownify+for+clipping+web+pages&url=https%3A%2F%2Fbrettterpstra.com%2F%2F2012%2F01%2F04%2Fscripting-readability-markdownify-for-clipping-web-pages%2F&via=ttscoff (Tweet this post)

Follow Brett on [Twitter][35] and [Mastodon][36].  
This content is [supported by readers like you.][37]

   [35]: https://twitter.com/ttscoff/
   [36]: https://nojack.easydns.ca/@ttscoff
   [37]: https://brettterpstra.com/support

Topics: [markdown][38], [productivity][39]

   [38]: https://brettterpstra.com/topic/markdown/
   [39]: https://brettterpstra.com/topic/productivity/

## Related posts:

  * [

##### A packing tape label maker hack

][40]
  * [

   [40]: https://brettterpstra.com/2018/05/01/a-packing-tape-label-maker-hack/

##### Cognitive Productivity With macOS: 7 Principles for Getting Smarter With Knowledge

][41]
  * [

   [41]: https://brettterpstra.com/2018/06/21/cognitive-productivity-with-macos-7-principles-for-getting-smarter-with-knowledge/

##### The Top 20 Apps not in my Dock

][42]
  * [

   [42]: https://brettterpstra.com/2019/06/19/the-top-20-apps-not-in-my-dock/

##### Stuff I've made (and actually use)

][43]

   [43]: https://brettterpstra.com/2019/01/15/stuff-ive-made-and-actually-use/

## Comments

All materials (C)2019 Brett Terpstra | [Twitter][44] | [Mastodon][45]

   [44]: https://twitter.com/ttscoff
   [45]: https://nojack.easydns.ca/@ttscoff
