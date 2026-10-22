# Site index · format 2
Structure and the names of what each page offers. Values that change often — prices, hours, phone,
address — and body copy are deliberately not recorded here; read the page itself for those.

## index.html → /
title: Business 0d3158d5-cdb4-4908-b0bf-9aab2692362b – Café
purpose: A landing page for a daylight café offering a contact form.
sections:
- `#hero` — Hero introduction: Café
- `#contact` "Say hello" — Contact form
also: The business description appears in the meta description tag, the Open Graph description tag, and the JSON-LD structured data block.

## support files
Files that are not pages. A line marked [content] holds words or data a visitor reads, so a
change to the site's content can land there; the rest only make the site work or look right.
- `llms.txt` — 48 bytes — too small to hold content
- `robots.txt` — 45 bytes — too small to hold content
- `sitemap.xml` — 160 bytes — too small to hold content

## shared (every page)
The header, navigation, mobile menu and footer are propagated from index.html to every other page by
`shell_propagation`. A change to any of them is made on index.html alone and copied automatically.
