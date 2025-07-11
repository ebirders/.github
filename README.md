# eBirders Project

The eBirders Project is a collection of libraries, Jupyter Notebooks,
Django apps, and Django sites for working with data from [eBird.org](https://ebird.org).

The projects, from the bottom of the stack, to the top, consist of:

* [ebird-codes](https://git.sr.ht/~smackay/ebird-codes) - constants, codes, 
  reference data, and utility functions that provide a single point of reference
  for all the eBird Projects.

* [ebird-api-requests](https://git.sr.ht/~smackay/ebird-api-requests) - a set of
  python functions for accessing the [eBird API 2.0](https://documenter.getpostman.com/view/664302/S1ENwy59)
  to download checklists, observations, locations and species, so you can 
  find out what has been seen, anywhere in the world.

* [ebird-scrapers](https://git.sr.ht/~smackay/ebird-scrapers) - alas, not
  all of the most interesting data is available via the eBird API. This 
  project provides scrapers for the "Recent Checklists" page, for any region,
  and for individual checklists.

* [ebird-api-data](https://git.sr.ht/~smackay/ebird-api-data) - a reusable
  Django app for loading data from the eBird API into a database. You can
  use this as the basic building block for doing analysis with Jupyter 
  Notebooks, or an entire web site.

* [ebird-dataset](https://git.sr.ht/~smackay/ebird-dataset) - a reusable
  Django app for loading data from eBird, this time from the  
  [eBird Basic Dataset](https://science.ebird.org/en/use-ebird-data/download-ebird-data-products).

* [ebird-notebooks](https://git.sr.ht/~smackay/ebird-notebooks) - a collection
  of Jupyter Notebooks for analysing data downloaded from the eBird API.

* [ebirders-pt](https://git.sr.ht/~smackay/ebirders-pt) - a Django based web
  site, delivering news and information on what has been seen in Portugal.
  Visit the site at [https://www.ebirders.pt](https://www.ebirders.pt).
