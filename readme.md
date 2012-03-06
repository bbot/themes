#Tumblr themes.

##Yet Another Atlantic

Features!

1. Uses HTML5 semantic tags throughout! The header is in a &lt;header&gt; block, each post is an &lt;article&gt;, post dates are inside (incorrect, nonstandard) &lt;time&gt; tags. The HTML5 outliner produces a correct outline. Shit's beautiful!
2. Uses <a href="http://sass-lang.com">Sass</a> to inline @import directives!
2. <a href="http://c1qfxugcgy0.tumblr.com/post/17714651298/responsive-design-hijinx">Theme scales from 3000 pixel wide monitors down to 320 pixel wide phones!</a>
3. <a href="http://c1qfxugcgy0.tumblr.com/post/17363683243/wait-a-minute">Code highlighting!</a>
4. Semantic "older posts" "newer posts" navigation links!
5. Minified CSS and HTML!
6. <a href="http://c1qfxugcgy0.tumblr.com/post/13182369086/how-to-use-css-to-format-pesterlog-text">Pesterchat formatted text!</a>
7. <a href="http://c1qfxugcgy0.tumblr.com/post/16071364335/theworstpersonintheworld-zachandmax-this">Yotsuba-themed posts!</a> That are kinda broken, and a real pain in the ass to write! This will be slightly less fucked in version 1.1.0!
8. No description field! If you let a Tumblr user describe themselves, they'll tell the world their age (14) their gender/orienation (asexual homoromantic) and favorite pony. (Rainbow Dash) YAA removes this temptation!
9. <a href="https://github.com/bbot/themes/commit/753a639b18efa19a30271042ca8e80750c01eeeb">Displays warning box for people using old versions of IE6,</a> because fuck those guys!
10. <a href="https://github.com/bbot/themes/commit/046249aa93df9b82312648f9c45653d214a3618f">UI interface for toggling stylesheet features!</a>
11. <a href="https://github.com/bbot/themes/commit/5e37d7236f65ba438b1ff9c5e322a5daf6ad2afa">CustomCSS!</a>
12. Released under the public domain &#8220;<a href="http://unlicense.org/">unlicense</a>&#8221;!

Bugs!

1. Some post types are implemented in the theme but don't have CSS rules. Will be fixed in 0.9.1
2. I went far, far out of my way to break compatibility with older browsers.
3. Doesn't validate! Tumblr appends a bunch of crap to any HTML they generate that makes almost any DTD fail validation, which is a shame.
4. There's a bit of a combinatorial problem with having four different blocks of CSS that people might want to toggle on and off. Rather than having 16 different versions of the stylesheet, there are only three: basic page styling, basic+code highlighting, basic+all the bells and whistles. This isn't as flexible as it could possibly be, but I don't care.
5. The CSS isn't quite the flawless masterpiece it could be.
