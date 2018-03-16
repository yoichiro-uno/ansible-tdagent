plugin_list:
 - fluent-plugin-elasticsearch
tdagent_confpath: /etc/td-agent
config_list:
  - accept_from_tdagent
  - send_to_elasticsearch
tag_name: sensordata
elasticsearch_host_ip: 172.21.11.147
elasticsearch_host_port: 9200
elasticsearch_type_name: sensordata
elasticsearch_index_name: fluentd
elasticsearch_logstash_prefix: sensordata
elasticsearch_flush_interval: 10s
elasticsearch_url: "http://172.21.11.147:9200"

