Python code 
- demonstrates use of OSF API to query PsyArXiv for number of uploads and details of individual preprints
- using webscraping via Selenium to take screenshot and extract some preprint details (view count, which is not (??) available via API
- make some graphs, save data as CSV
- post results to [@PAXscraper](https://mastodon.social/@PAXscraper) on mastodon

API docs https://developer.osf.io/#tag/General-Usage

Uses conda for reproducibility

Get your API tokens from OSF and mastodon and store in the files from which these are loaded

For all functions to work create folders 
 \data
 \archive

Key demo of the API use is the function <get_preprints> which is currentrly line 243 in paxscrape.py 
