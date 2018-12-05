An unfinished (and abandoned) version of [GG](https://github.com/Good-Old-Downloads/gg) made for [ZeroNet](https://zeronet.io/).  
Create a new ZeroNet site by clicking "Create new, empty site", then copy the contents of this repo to `/data/generated-site-address`. You probably also need to edit or delete `content.json`

## Differences compared to GG

Changes are mostly to try to keep the site within the file size limit of 10MB.

* Fonts (Roboto, FontAwesome) are loaded from a CDN instead of being self hosted.
* Some unnecessary/unused styles are removed
* Removed Donate, Queue, and Admin pages.
* Search is simplified (should be able to make this work like the normal site in the future)

## Todo

* Still a lot of leftover CSS that's unused in this version, can save a lot of space by removing them.
* Load background images from GOG instead of being self-hosted (images.gog.com)
* Optimize handlebars templates, current implementation is a quick hackjob
* Reimplement some javascript from normal site. (Background loading, changelog from GOG api)