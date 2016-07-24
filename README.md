# What to monitor

Monitoring guide to DevOps.

## AWS

* [Upcoming AWS maintenance event occurs](more_in_depth/upcoming_aws_maintenance_event_occurs.md)

## Host

AWS EC2 instances and others.

* [NTP sync](https://help.datadoghq.com/hc/en-us/articles/204282095-Network-Time-Protocol-NTP-Offset-Issues)

* Disk usage is too high

  For instance,

  * When over 80% is being used for web container node
  * When over 70% is being used for database storage

* Disk IO is too high

* CPU utilization is over 90% for more than a minute


### Recommended reads

* [Network Time Protocol \(NTP\) Offset Issues](https://help.datadoghq.com/hc/en-us/articles/204282095-Network-Time-Protocol-NTP-Offset-Issues)

## Process

* Zombie process is found
* Target process is not running

## Load balancer

AWS ELB, Haproxy and others.

* [Increased round-trip latency between the load balancer and backends](more_in_depth/increased_round_trip_latency.md)
* [Increased error rates including 5xx, 4xx and others](more_in_depth/increased_error_rates.md)
* [Surged requests per second](more_in_depth/surged_requests.md)
* SSL certification will be expired soon

### Recommended reads

* [DataDog SSL Expires Check](https://workshop.avatarnewyork.com/project/datadog-ssl-expires-check/)

## JVM

* `OutOfMemory error`

## MySQL

* Too many threads connected
* Low key cache hit rate
* Low table cache hit rate
* Low query cache hit rate
* Low buffer pool hit rate
* Low index usages
* Deadlock is detected
* Too long queries per second
* Too much reads or writes per second

### MySQL Cluster

* [Long slave lag](/more_in_dpeth/long-replication-lag.md): Slave lag means the delay between Master and Slave in second

### Recommended reads

* [check\_mysql\_health](https://labs.consol.de/nagios/check_mysql_health/) is a Nagios plugin to check various parameters of a MySQL database.

## Message Queue

### Message Queue Cluster

* Long replication lag

## License

To the extent possible under law, [Jaehoon Choi](https://andromedarabbit.net) has waived all copyright and related or neighboring rights to this work.

