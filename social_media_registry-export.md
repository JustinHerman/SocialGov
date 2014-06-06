## Background

The Social Media Registry contains over 3,000 official government accounts - available for lookup via [this page](http://www.usa.gov/Contact/verify-social-media.shtml) or [via API](http://www.usa.gov/About/developer-resources/social-media-registry.shtml).  

## How to Export

The Registry API provides access to the catalog in XML and JSON, but with pagination that contains 100 records per page.  

This [jsfiddle snippet](http://jsfiddle.net/Vab7V/3/) concatenates the 12+ pages of results that represent the complete list of Facebook accounts in the registry.  

By taking the resulting json file that resolves in the bottom right box on that [page](http://jsfiddle.net/Vab7V/3/)) and running it through this [JSON -> CSV tool](http://konklone.io/json), one ends up with a file that can be opened in a spreadsheet program.  

Here is a [permalink to the end product](http://konklone.io/json/?id=644c62c159a300225b98) as of June 5, 2014, with a direct link to the csv [here](https://raw.githubusercontent.com/gbinal/SocialGov/patch-3/SMR-facebook-export_6-6-14.csv) [right click on the link and save].  




