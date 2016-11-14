Installation notes:

1- check_ram REQUIRES /opt/sensu/embedded/bin/gem install vmstat
2- gem install sensu-plugins-postgres REQUIRES yum -y install postgresql-devel

Required sensu gems:

- sensu-plugins-disk-checks
- sensu-plugins-redis
- sensu-plugins-process-checks
- sensu-plugins-postgres
- sensu-plugins-rabbitmq
- sensu-plugins-filesystem-checks
- sensu-plugins-memory-checks
- sensu-plugins-cpu-checks
- sensu-plugins-network-checks
- sensu-plugins-load-checks
- sensu-plugins-nginx
- sensu-plugins-graphite
- sensu-plugins-elasticsearch
- sensu-plugins-ntp

List of gems which are required to be present on offline repo / Other required gems come with sensu installation

activesupport (4.2.5)
array_stats (0.6.0)
aws-es-transport (0.1.4)
aws-sdk (2.6.5)
aws-sdk-core (2.6.5)
aws-sdk-resources (2.6.5)
bunny (1.7.0)
carrot-top (0.0.7)
dentaku (2.0.4)
dnsbl-client (1.0.2)
domain_name (0.5.20160826)
elasticsearch (1.0.18)
elasticsearch-api (1.0.18)
elasticsearch-transport (1.0.18)
english (0.6.3)
faraday (0.9.2)
faraday_middleware (0.10.0)
http-cookie (1.0.3)
i18n (0.7.0)
jmespath (1.3.1)
language (0.6.0)
linux-kstat (0.1.3 universal-linux)
mime-types (2.99.3)
multi_json (1.12.1)
multipart-post (2.0.0)
net-ping (1.7.8)
netrc (0.11.0)
pg (0.18.3)
redis (3.2.1)
rest-client (1.8.0)
sensu-plugins-cpu-checks (1.0.0)
sensu-plugins-disk-checks (2.0.1)
sensu-plugins-elasticsearch (1.0.0)
sensu-plugins-filesystem-checks (0.2.0)
sensu-plugins-graphite (2.0.0)
sensu-plugins-load-checks (1.0.0)
sensu-plugins-memory-checks (1.0.2)
sensu-plugins-network-checks (1.1.0)
sensu-plugins-nginx (2.0.0)
sensu-plugins-ntp (1.0.0)
sensu-plugins-postgres (0.1.1)
sensu-plugins-process-checks (1.0.0)
sensu-plugins-rabbitmq (1.3.1)
sensu-plugins-redis (1.0.0)
simple-graphite (2.1.0)
stomp (1.3.4)
sys-filesystem (1.1.5)
sys-proctable (0.9.8 universal-linux)
thread_safe (0.3.5)
tzinfo (1.2.2)
unf (0.1.4)
unf_ext (0.0.7.2)
whois (3.6.3)

Guideline about offline usage of this playbook:

https://books.sonatype.com/nexus-book/reference3/rubygems.html#rubygems-config