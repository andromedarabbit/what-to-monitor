# what-to-monitor

Monitoring guide to DevOps:

## AWS

- [ ] Upcoming AWS maintenance event occurs

## Host

EC2 instances,

- [ ] [NTP sync](https://help.datadoghq.com/hc/en-us/articles/204282095-Network-Time-Protocol-NTP-Offset-Issues)
- [ ] Disk usage is too high
  - [ ] When over 80% is beging used for web container node
  - [ ] When over 70% is beging used for database storage
- [ ] Disk IO is too high
- [ ] CPU usage is over 90% for more than a minute


## Load balancer

AWS ELB, Haproxy

![](https://www.evernote.com/l/AAWYHFEJCF1CYLrdmAgKtbfnA1JIr5DQcaMB/image.png)

- [ ] Increased latency between the load balancer and backends
- [ ] Increased latency between the load balancer and frontends
- [ ] Increased error rates including 5xx, 4xx and others


## JVM

- [ ] `OutOfMemory error`
