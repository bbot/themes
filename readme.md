#Tumblr themes.

##Yet Another Atlantic

Features!

1. Uses HTML5 semantic tags throughout! The header is in a &lt;header&gt; block, each post is an &lt;article&gt;, post dates are inside (incorrect, nonstandard) &lt;time&gt; tags. The HTML5 outliner produces a correct outline. Shit's beautiful.
2. <a href="http://c1qfxugcgy0.tumblr.com/post/17714651298/responsive-design-hijinx">Theme scales from 3000 pixel wide monitors down to 400 pixel wide phones.</a>
3. <a href="http://c1qfxugcgy0.tumblr.com/post/17363683243/wait-a-minute">Code highlighting!</a>
4. Semantic "older posts" "newer posts" navigation links.
5. Minified CSS and HTML.
6. <a href="http://c1qfxugcgy0.tumblr.com/post/13182369086/how-to-use-css-to-format-pesterlog-text">Pesterchat formatted text!</a>
7. <a href="http://c1qfxugcgy0.tumblr.com/post/16071364335/theworstpersonintheworld-zachandmax-this">Yotsuba-themed posts!</a> That are kinda broken, and a real pain in the ass to write! This will be slightly less fucked in version 1.1.0.

Bugs!

1. Some post types are implemented in the theme but don't have CSS rules. Will be fixed in 0.9.1
2. I went far, far out of my way to break compatibility with older browsers. If you're using Internet Explorer, you can go ahead and fuck a tree.
3. Doesn't validate! Tumblr appends a bunch of crap to any HTML they generate that makes almost any DTD fail validation, which is a shame.
4. There's a bit of a combinatorial problem with having four different blocks of CSS that people might want to toggle on and off. Rather than having 16 different versions of the stylesheet, there are only three: basic page styling, basic+code highlighting, basic+all the bells and whistles. This isn't as flexible as it could possibly be, but I don't care.
5. The CSS isn't quite the flawless masterpiece it could be.

Implementation details!

1. Each stylesheet is generated from snippets using YUIcompressor's @import faculty. This means I only have to edit the CSS in one spot, to have to automatically propgate to each minified stylesheet, like we're living in the fucking *future.*
