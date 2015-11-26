# iso-elk-stack

The UCLA Information Security Office customized an integration of Logstash, Elasticsearch, and Kibana (the "ELK stack") to extract security-specific information, richly visualize that data, and create notifications based on specific concerns. 

As of November 25th, 2015, this project has been updated to reflect the major changes reflected in Elasticsearch 2.1, Logstash 2.1, and Kibana 4.3. In addition, support for Filebeat, Packetbeat, and Topbeat was added and documentation is available at the link below.

For installation instructions for both the central ELK server and client servers (that use log-courier to ship events to the central ELK server), please visit the following link and select the "Install" tab: https://www.itsecurity.ucla.edu/elk
