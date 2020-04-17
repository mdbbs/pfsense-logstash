# pfsense-logstash
A simple logstash config for parsing pfsense syslog data. Parsing for Elastic 7.x. 

Todo:
+ Work on parsing other types of events, DHCP, DNS, routing, etc.
+ Align fields with Elastic ECS: https://github.com/elastic/ecs
 
filter conf file, grok filter and grok patterns used from: https://github.com/patrickjennings/logstash-pfsense
