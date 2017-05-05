# Immowelt Scraper Service

This node service scrapes all available entries for a given city from http://immowelt.de and stores them in a simple Json file store.

To make the scraped data available, the service exposes an API with 2 GET endpoints:
* `GET /api/entries` - All scraped entries
* `GET /api/entry/{entryId}` - An entry by its Immonet ID

By default this service starts its API on `localhost:1234`.

Props to [Federico Bertolini](https://github.com/fedebertolini) for writing [immowelt-scraper](https://www.npmjs.com/package/immowelt-scraper) :)
