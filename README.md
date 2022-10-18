# C316

Dummy is a content generation toolkit designed to make the development, testing and presentation of web prototypes less time consuming and more realistic. It does so by making it easy to populate static HTML with dynamic content, and by randomizing elements within a layout on subsequent loads of a document, in a way, simulating connectivity to a live database.

### Dummy can…
+ Flesh out highly variable, asset rich layouts quickly with friendly, human-readable logic for building loops and controlling probability.
+ Allow you to focus on the important things – namely, the design and the code – not on copying and pasting (static) Lorem Ipsum, or hunting down plausible placeholder images.
+ More. Not lots more, but a _bit_ more!

### You can…
+ Watch a screencast at https://vimeo.com/42252088
+ Ask questions and direct misgivings to http://twitter.com/kerns
+ Fork, follow or download via https://github.com/kerns/dummy

### More Info
Dummy's primary goal is to provide tools that speed front-end prototyping and QA. Whether you're meticulously crafting a fully responsive site with a myriad of CSS breakpoints, or just slapping together a half-baked idea – using Dummy should make it easier _at the earliest stages of development_ to visualize, test and present something much closer to what your actual front-end will become under a variety of different conditions.


**Dummy is for the front-end web worker who wonders…**

+ How does this layout hold up with and without an image, or with multiple images?
+ What is the maximum number of items that can appear in this list before it breaks the layout, or before it just stops looking good?
+ How do the columns align and balance as the amount of content changes – or what's the longest word that can fit into this column without triggering unwanted overflow?
+ What is the easiest way to demo the signed-in and signed-out states of this page?

### Why?
Using Dummy in the early stages of front-end development can give you a new perspective on your work every time your document is reloaded in the browser, shortening and improving your test cycle by more quickly exposing weak-points or trouble areas as you go about marking up a new design. It's like watching a time-lapse video of your layout performing with real data.

### Requirements
You need a development environment running Apache + PHP and compiled with support for GD (this covers most of them). If you want to play with URL segments or other advanced techniques then you'll need to have mod_rewrite enabled, and you'll need to enable the .htaccess file (included in /dummy/extras/), but again, this probably covers most local development environments. If you're not developing locally, …why aren't you developing locally?

### TODO
+ Ability to call and define image crops from within CSS (i.e. ability to post image requests in the URL to dummy.php)
+ Develop an easy way to link our broadcast dumb_luck outcomes, so that one outcome could bubble-over to another.
+ Clean up the way errors and messages are formatted (i.e. abstract the HTML and inline styles that surround them)
+ The image assets that ship with Dummy are highly geared for usage in editorial design. One could imagine separate asset packages for different types of projects (e.g. a commerce package with commercial product shots, a portfolio or gallery package with images that showcase art, architecture, or design).

### Credits
Credits can be found in dummy/CREDITS.md
