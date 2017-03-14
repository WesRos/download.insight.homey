# download.insight.homey
Script to automaticly download Insight data from Homey.

When you whats to view Homey insight information in another software application, like: Nagios, Grafana, Domotics. Or you want to be sure you dont miss anything. You could download all the InSight information with this script.

This Script generates the "curl_commands"-Script. Add the "curl_commands"-Script in cron and this goes automaticly.

Requirments:
curl
jq

