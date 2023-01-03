# Web Dev Text Replacements for TextExpander (macOS and Windows app)

For [TextExpander](https://textexpander.com/), you need to go to your account profile on the web site, then choose 'Import/Export'. There you can add files that will be imported in to your library as snippets.

Note that the format is simply a CSV, so these will have the trigger and the expanded content in. The collection name is derived from the .csv filename. With the WCAG entries, the filename is set to 'WCAG 2.1' rather than 'WCAG 2.1...' because otherwise TextExpander truncates at the first instance of '.', resulting in all WCAG 2.1 entries being shown as

* WCAG 2
* WCAG 2
* WCAG 2
* WCAG 2

Rather than 

* WCAG 2_1 - Links
* WCAG 2_1 - Links - Markdown
* WCAG 2_1 - Understanding
* WCAG 2_1 - Understanding - Markdown

## Trigger format

How to trigger these text replacements:

### HTML Reference

(Where `kbd` is the HTML element you are getting a link for; change according to the element that you need)

* HTML reference - link. Trigger format = !kbd-l 
* HTML reference - Markdown link. Trigger format = !kbd-md

### WCAG SC Links

(Where `1.1.1` is the SC you are getting a link for; change according to the SC that you need)

* WCAG 2.1 - Link. Trigger format = 1.1.1-l
* WCAG 2.1 - Markdown link. Trigger format = 1.1.1-md
* WCAG 2.1 - Understanding - Link. Trigger format = 1.1.1-u-l
* WCAG 2.1 - Understanding - Markdown link. Trigger format = 1.1.1-u-md
