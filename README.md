# iso-elk-stack

########IMPORTANT########
Very soon, we'll be releasing an entirely new configuration for Elasticsearch 2.0, Logstash 2.0, and Kibana 4.2 (in the aftermath of the major Elasticsearch and Logstash upgrades announced last month). Literally a few hours after the update, we started ripping down our existent configuration for UCLA-ISO-ELK to rebuild it for the next version of the ELK stack. Stay tuned!
: 

The UCLA Information Security Office customized an integration of Logstash, Elasticsearch, and Kibana (the "ELK stack") to extract security-specific information, richly visualize that data, and create notifications based on specific concerns.

Note:
For installation instructions for both the central ELK server and client servers (that use log-courier to ship events to the central ELK server), please visit the following link and select the "Install" tab: https://www.itsecurity.ucla.edu/elk
