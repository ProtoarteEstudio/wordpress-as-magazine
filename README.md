wordpress-as-magazine
=====================

Wordpress hacks, plug-ins and settings we use on [The Civic Beat Reader](http://reader.thecivicbeat.com) to make it a fully fledged online magazine


**General**

- [Wordpress Multisite](http://codex.wordpress.org/Create_A_Network): Simply the easiest way to create and maintain multiple sites. Having multisite turned on at the offset also allows us to add in content channels later when we expand.


**Themes**

- [Bones](http://themble.com/bones/): Marketed as "The HTML5 Wordpress Starter Theme," we use Bones over other frameworks because it's straightforward and simple, and because we end up writing the styling code from scratch anyway. Bones does provide us with a responsive grid framework as well, and has SCSS and LESS support.


**Plug-ins (specific)**

- [Co-Authors Plus](http://wordpress.org/plugins/co-authors-plus/): Allows multiple authors to be credited for a post, as well as guest authors (who don't need to have an account on your Wordpress setup). Great when we collaborate on more complex pieces, or when one person researches while another writes.
- [Secondary HTML Content](http://get10up.com/plugins/secondary-html-content-wordpress/): This lets us have a second rich text block for our posts. In our [Reader](http://reader.thecivicbeat.com), we use this for our *Learn More* section that goes at the end of each article.
- [Show Private](http://amib.ir/weblog/?p=153): Allows post drafts to be published at a private URL. Great for getting feedback on a document from people who might not otherwise want to log into the Wordpress dashboard and find it there. (Or who don't have access to the Wordpress dashboard!)
- [Side Matter](http://wordpress.org/extend/plugins/side-matter/): Brilliant, brilliant plug-in that creates what we think of as webpage footnotes – that is, footnotes that go on the left or right of the text. This makes them accessible where having a footnote at the bottom of a long article is an accessibility nightmare.


**Plug-ins (general)**

- [Feed Statistics](http://www.chrisfinke.com/wordpress/plugins/feed-statistics/): Get a count of how many RSS subscribers you have! Important!
- [Google Analaytics MU](https://github.com/foe-services/google-analytics-mu): Supports networks better than most other Google Analytics plug-ins. But apply the [second fix from here](http://www.netcel.com/Resources/Insights/White-papers/6-must-have-google-analytics-filters/) to get proper subdomain support.
- [Jetpback by Wordpress.com](http://wordpress.org/plugins/jetpack/): Little add-ons helpful. The killer feature for me is the Site Stats, which lets me get visitor stats without leaving the Wordpress dashboard.
- [Types](http://wordpress.org/extend/plugins/types/): We use custom types for our Countries/Place metadata, and the Types plug-in gives us a nice GUI to do that.
- [W3 Total Cache](http://www.w3-edge.com/wordpress-plugins/w3-total-cache/): We don't have enough traffic to know whether this makes a difference but it was highly recommended by other sites and blogs.


*For more, also see Chris Coyier's list of [Wordpress Plugins I Use](http://css-tricks.com/wordpress-plugins-i-use/) on CSS Tricks.*
