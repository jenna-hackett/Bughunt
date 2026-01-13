# Tasks - What needs to be done and where.

Markdown for quick notes on issues to fix/look into after a first read through of each file.

## General Tasks

- [x] Add a `.gitignore` file and...
- [!!!] include `node_modules` in it
- [ ] Organize all static assets `(e.g., images from the broken project)` into the asset directory.

## HTML

- [x] script tag should to have `defer` in it so the JS loading doesn't cause issue for the HTML.
- [x] JavaScript file name needs to be changed from index.js to script.js
- [x] Unnecessary `/` on closing tags for some elements. Ie: meta charset and meta name.
- [x] Instead of divs, use an unordered list for nav menu.
- [x] Header, main, body and footer tags would be helpful semantic elements. `EX: first div tag should be a header.`
- [x] All h1 headings. Main heading should be h1 but the `sub-headers should be downsized accordingly.`
- [x] Turn the article section into a semantic article element.
- [x] Need SECTIONS, not so many random div tags.
- [x] Check out divs at bottom of page (there just seem to be a lot...?) -Look for tags that are not closed and that things are properly nested.
- [x] Use validator to help with syntax errors. (Checked: Passed validator with no errors or warnings.)
- [x] Ensure `image and alt text` are edited to working order.

## CSS

- [x] Nav bar needs css for proper alignment.
- [x] `header h0` is being targeted on `line 27 and 142`... this... does not exist.
- [x] Check: What does `:last child` mean/do? - (Checked: Targets the last element inside a parent container. Removed.)
- [x] General proof-read for any typos
- [x] NEGATIVE values!!!
- [x] Browser inspector for visibility issues.
- [x] ul li:hover {transform: translateX(4px);}. `translateX` is a new one for me. Not sure if spelling mistake or no. (Checked: Not a spelling error. Removed.)
- [x] The CSS must be responsive and use an `accessible color scheme`.
- [x] Should we be using all one value of measurement? `IE: All rem or all pixels`. (Checked: Hybrid approach seems to be best since different areas of the webpage have different needs.)
- [ ] Combine CSS styling where applicable to reduce code redundancy.

## JavaScript

- [x] no `","` after Skywalker.
- [ ] Check: Browser console!!!
