Simple Metricbeat setup for elasticsearch cluster monitoring

Prerequisits: 

 - An already running ES production cluster we refer to as ES_ADDON_HOST, user and password
 - An already running ES monitoring cluster we refer to as ES_MONITORING_ADDON_HOST
 - A custom Kibana user for the monitoring cluster, with the following roles : 
   kibana_admin, beats_system, kibana_system, monitoring_user, remote_monitoring_collector, remote_monitoring_agent, metricbeat_setup

