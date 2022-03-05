Files

	HalalanResults.csv - extracted data + cleaning
	20220305_HalalanResults_raw.json - raw extracted data
	failed_urls.txt - list of auto generated url's that failed to load

Scraping process

	generate url of each city/town
	
	for each url
		extract all tables

Variables
	
	'url': url where the table was extracted 
	['region_id','province_id','city_id'] : unique code extracted from website.
	'province_name': name of province
    ['position', 'candidate_name', 'political_party', 'vote_count'] 
    'rank': taken per table in the html (recommended to not use this)


