# Tasks

Markdown for quick notes on issues to fix after a first read through of the code.

## General Tasks

[ ] Organize all static assets (e.g., images from the broken project) into the asset directory.
[x] Add a `.gitignore` file and [!!!] include `node_modules` in it

## HTML

[x] script tag should to have `defer` in it so the JS loading doesn't cause issue for the HTML.
[x] Unnecessary `/` on closing tags for some elements. Ie: meta charset and meta name.
[x] Instead of divs, use an unordered list for nav menu.
[x] Header, main, body and footer tags would be helpful semantic elements. `EX: first div tag should be a header.`
[x] All h1 headings. Main heading should be h1 but the following `sub-headers should be downsized accordingly.`
[ ] Ensure `image and alt text` are edited to working order(?). Currently empty.
[x] Can the article section be as a semantic article element instead of the divs?
[x] Need SECTIONS, not so many random div tags.
[x] Check out divs at bottom of page (there just seem to be a lot...?) -Look for tags that are not closed and that things are properly nested.
[ ] Use validator to help with syntax errors.

## CSS

[x] Nav bar needs css for proper alignment.
[~] `header h0` is being targeted on `line 27 and 142`... this... does not exist. Needs to be fixed after the HTML has been ironed out.
[ ] Check: Places where `clamp` could be replaced/inserted. -Check: Flexibility of the page at different sizes.
[x] Check: What does `:last child` mean/do? - Targets the last element inside a parent container.
[ ] General proof-read for any typos
[ ] Browser inspector`(?)` for visibility issues.
[ ] Should we be using all one value of measurement? `IE: All rem or all pixels`... Something to google(best practices).
[ ] ul li:hover {transform: translateX(4px);}. `translateX` is a new one for me. Not sure if spelling mistake or no.
[ ] The CSS must be responsive and use an `accessible color scheme`.

## JavaScript

[x] no `","` after Skywalker.
[ ] Other simple syntax issues?
[ ] Check: Browser console!!!
