#Tumblr themes.

##Yet Another Atlantic

Features!

#.Uses HTML5 semantic tags throughout! The header is in a &lt;header&gt; block, each post is an &lt;article&gt;, post dates are inside (incorrect, nonstandard) &lt;time&gt; tags. The HTML5 outliner produces a correct outline. Shit's beautiful.
#.<a href="http://c1qfxugcgy0.tumblr.com/post/17714651298/responsive-design-hijinx">Theme scales from 3000 pixel wide monitors down to 400 pixel wide phones.</a>
#.<a href="c1qfxugcgy0.tumblr.com/post/17363683243/wait-a-minute">Code highlighting!</a>
#.Semantic "older posts" "newer posts" navigation links.
#.Minified CSS and HTML.
#.<a href="http://c1qfxugcgy0.tumblr.com/post/13182369086/how-to-use-css-to-format-pesterlog-text">Pesterchat formatted text!</a>
#.<a href="http://c1qfxugcgy0.tumblr.com/post/16071364335/theworstpersonintheworld-zachandmax-this">Yotsuba-themed posts!</a> That are kinda broken, and a real pain in the ass to write! This will be slightly less fucked in version 1.1.0.

Bugs!

#.Some post types are implemented in the theme but don't have CSS rules. Will be fixed in 0.9.1
#.I went far, far out of my way to break compatibility with older browsers. If you're using Internet Explorer, you can go ahead and fuck a tree.
#.Doesn't validate! Tumblr appends a bunch of crap to any HTML they generate that makes almost any DTD fail validation, which is a shame.
#.There's a bit of a combinatorial problem with having four different blocks of CSS that people might want to toggle on and off. Rather than having 16 different versions of the stylesheet, there are only three: basic page styling, basic+code highlighting, basic+all the bells and whistles. This isn't as flexible as it could possibly be, but I don't care.
#.The CSS isn't quite the flawless masterpiece it could be.
