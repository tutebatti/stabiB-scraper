# stabiB-scraper
Scraping information of mss at StaBi Berlin

## Procedure

- use ppn_scrawler to create list of xml urls
- download all xml files using `xargs < xml_urls wget`
- use `cat_xmls.sh` to concatenate xml files into one file
