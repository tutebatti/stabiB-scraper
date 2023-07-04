# stabiB-scraper
Scraping information of mss at StaBi Berlin

## Procedure

- use ppn_scrawler to create list of xml urls
- download all xml files using `xargs < xml_urls wget`
- use `cat_xmls.sh` to concatenate xml files into one file
- use xslt processor to convert `all_data.xml` to csv using `xml2csv.xsl`

## To do

- add correct handling of multivolume manuscript entries
- improve handling of dates
- strip first empty line in csv output
