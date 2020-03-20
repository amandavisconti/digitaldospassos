# digitaldospassos.com migration omeka=>static site
Repo for the code running the static version of my 2010 Omeka website exploring media in the "newsreel" sections of John Dos Passos' novel 1919. The static "archive" verison of the site is live and can be visited at [DigitalDosPassos.com](http://digitaldospassos.com).

This was an Omeka site I made in lieu of a final paper for a graduate seminar back in 2010. I never got around to updating its Omeka (it was on something like 1.2.1?) and the CMS isn't required for the important parts to work, so I'm finally migrating it to a static site. Omeka is *awesome* and you should consider it for digital exhibits, archival collections, and other DHy website needs (especially those where multiple people will be adding or editing items, and/or you'll have a lot of items). The Omeka team has stellar user support, too. I'm just switching because I haven't made the time to keep my site updated/secure in five years, I don't want to add/edit the site any further, and the functionalities I care about are retained with a flat HTML version of the site.

The static site's web hosting is via this repo here, using GitHub Pages. I left the repo public in case it helps anyone to look at the code, but note that it's pretty messy (I used Site Sucker and some find+replace to make the site work this way). If you're curious about static websites and/or free website hosting on GitHub Pages, you may enjoy [my novice-friendly, peer-reviewed lesson on this topic over at *The Programming Historian*](programminghistorian.org/lessons/building-static-sites-with-jekyll-github-pages).

## What's retained:  
1. the item index
2. individual item pages

## What's gone/changed:  
0. changed: fancy interactive javascript image pile as non-linear entry to the collection on the front page; the front page is also missing CSS styling and does not look like the original site's homepage at all
1. gone: the search/advanced search functions (could recreate these via JS, didn't feel like it—site only has like 24 items to search through)  
2. gone: login, which allowed individual site visitors to "curate" items on the site (I don't remember exactly how this worked or if I ever fully implemented it, but I think it used the Exhibit Builder plugin?)  
3. changed: text in foot to indicate this is no longer an Omeka site, a couple pieces of texts replacing removed features (e.g. search form, login/forgotten password links)
