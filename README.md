# Human Centered Data Science - A1: Data Curation

The goal for this assignment is to analyze, and publish a dataset of monthly traffic on English Wikipedia from January 1 2008 through August 30 2020. I retrieve 5 sets of data using Legacy Pagecounts and the Pageviews APIs and perform data cleansing and analysis to gain deeper understanding on total visits by device types. 

# Data Sources
Two different API endpoints, the Legacy Pagecounts API and the Pageviews API.

The [Legacy Pagecounts API](https://wikimedia.org/api/rest_v1/#!/Pagecounts_data_(legacy)/get_metrics_legacy_pagecounts_aggregate_project_access_site_granularity_start_end) provides access to desktop and mobile traffic data from December 2007 through July 2016. For complete documentation, visit [here](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts).

The [Pageviews API](https://wikimedia.org/api/rest_v1/#!/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end) provides access to desktop, mobile web, and mobile app traffic data from July 2015 through last month. For complete documentation, visit [here](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews).

See the License section below for important legal information.

# Output Schema
The data output (en-wikipedia_traffic_200712-202008.csv) includes eight columns with the definition as follows:

Column | Description | 
Year | Reporting year of the website traffic  | 
Month | Reporting month of the website traffic | 
pageview_mobile_views| monthly pageview count of mobile devices recorded by Pageviews API  | 
pageview_desktop_views| monthly pageview count of desktop recorded by Pageviews API  | 
pageview_all_views | monthly pageview count of desktop and mobile devices recorded by Pageviews API |
pagecount_mobile_views | monthly pagecount of mobile devices recorded by the legacy API| 
pagecount_desktop_views | monthly pagecount of mobile desktop recorded by the legacy API |
pagecount_all_views | monthly pagecount of desktop and mobile devices recorded by the legacy API|



# License
Wikimedia Foundation [Term of Use](https://www.mediawiki.org/wiki/Wikimedia_REST_API#Terms_and_conditions) and [Privacy Policy] (https://foundation.wikimedia.org/wiki/Privacy_policy)

