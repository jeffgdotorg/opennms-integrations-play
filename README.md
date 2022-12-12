# opennms-integrations-play
Miscellaneous work to show integrations to / from OpenNMS.
Most of this work is experimental and/ or incomplete but it may provide a starting point for real production examples.

## Kafka Experiments and experimental drools rules
This is an overlay project containing example CHUBB camera alarm creation and forwarding through kafka bus and also drools examples

[kafka-experiments](../main/kafka-experiments)

### chubb mib 
Creation of chubb alarm objects from chub mib files

[chubb-mib](../main/kafka-experiments/chubb-mib) 

### integration-example-1
Simple kafka alarm client and a web ui which receives alarms from OpenNMS over kafka alarm forwarding bus
[integration-example-1](../opennms-integrations-play/kafka-experiments/integration-example-1) 

### minimal-minion-kafka  (with drools)
Example OpeNNMS configuration using chubb event definitions ande chubb-rules.drl file to create alarms
[minimal-minion-kafka](../opennms-integrations-play/kafka-experiments/minimal-minion-kafka) 

## pris-docker-compose
[pris-docker-compose](../main/pris-docker-compose) 

is an example project for using pris with an excel spreadsheet to provision OpenNMS

## iptablesexample1
[iptablesexample1](../main/iptablesexample1)

Is a simple example of using iptables to map ports to differnt ip addresses so that OpenNMS can poll snmp agents on differnt ports.

## multi-opennms-newts-docker (Incomplete)
[multi-opennms-newts-docker](../main/multi-opennms-newts-docker)

Is a simple project with several opennms pointing at single casandra

## onmsIntegrationExample1 
[onmsIntegrationExample1](../main/onmsIntegrationExample1)

Example integrating openNMS to simple ReST api for TTOC solution - not used in project


## scriptdtest
[scriptdtest](../main/scriptdtest)

Example project integrating scriptd


## events to rester (Incomplete)
[eventstorester](../main/eventstorester)

is an example project to create a rester postman configuration from OpenNMS eventconfig.xml





