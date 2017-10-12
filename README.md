# monitoring_insight_facebook_zabbix

To use this script on facebook you must have an ACCESS TOKEN generated and the page number

1. Add to the following lines in the zabbix configuration file:

UserParameter = monitoring_facebook.py [*], python /externalscript/monitoring_facebook.py $ 1 $ 2 $ 3

Template: template_insight_facebook.xml.

2. On script:

access_token=<your access token generated>
  
page_id=<id page>
  
more information:
https://pt.slideshare.net/bezalielramos/monitoring-your-fanpagefacebookwithzabbix/edit?src=slideview&type=privacy
