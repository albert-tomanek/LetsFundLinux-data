If your app's or website's donation links do not show up in LetsFundLinux, add it to one of the files below and open a pull request.

### Do edit

* `apps.json` -- Donation links for Flatpak (so far only) apps
* `websites.json` -- Donation links for websites

### Do _not_ edit

* `apps.scraped.json` -- This is the output of a script (`scrapers/donation_scraper.py`). If the script failed to scrape donation links off your homepage, add them manually to `apps.json`. It overrides this file.
