# eBirders Project

The eBirders Project is a collection of libraries, Jupyter Notebooks,
Django apps, and Django sites for working with data from [eBird.org](https://ebird.org).

The projects, from the bottom of the stack, to the top, consist of:

* [ebird-api-requests](https://github.com/ebirders/ebird-api-requests) - a set of
  python functions for accessing the [eBird API 2.0](https://documenter.getpostman.com/view/664302/S1ENwy59)
  to download checklists, observations, locations and species, so you can 
  find out what has been seen, anywhere in the world.

* [ebird-api-data](https://github.com/ebirders/ebird-api-data) - a reusable
  Django app for loading data from the eBird API into a database. You can
  use this as the basic building block for doing analysis with Jupyter 
  Notebooks, or an entire web site.

* [ebird-api-explorer](https://github.com/ebirders/ebird-api-explorer) - a 
  Django-based web site for browsing a database containing observations from the  
  eBird API.

* [ebird-dataset-data](https://github.com/ebirders/ebird-dataset-data) - a reusable
  Django app for loading data from eBird, this time from the  
  [eBird Basic Dataset](https://science.ebird.org/en/use-ebird-data/download-ebird-data-products).

* [ebird-dataset-explorer](https://github.com/ebirders/ebird-dataset-explorer) - a 
  Django-based web site for browsing a database containing observations from the  
  eBird Basic Dataset.

* [ebird-notebooks](https://github.com/ebirders/ebird-notebooks) - a collection
  of Jupyter Notebooks for analysing data downloaded from the eBird API.

* [ebird-pages](https://github.com/ebirders/ebird-pages) - alas, not
  all of the most interesting data is available via the eBird API. This 
  project provides scrapers for the "Recent Checklists" page, for any region,
  and for individual checklists.

# Licenses

All eBirders projects are released under the terms of the `[MIT](https://opensource.org/licenses/MIT) license.
