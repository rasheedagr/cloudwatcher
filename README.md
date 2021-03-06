cloudwatcher
============

Collects memory, swap, and disk space utilization on an Amazon EC2 instance and sends this data as custom metrics to Amazon CloudWatch periodically.

Usage
=====

To start `cloudwatcher` daemon you simply run:

    $ cloudwatcher

You can also query Amazon CloudWatch API for recent statistics:

    $ cloudwatcher statistics

Metrics
=======

- Memory Utilization (%)
- Memory Used (MB)
- Memory Available (MB)
- Swap Utilization (%)
- Swap Used (MB)
- Disk Space Utilization (%)
- Disk Space Used (GB)
- Disk Space Available (GB)

Todo
====

* [x] Fix disk space conversion
* [x] Fix InvalidClientTokenId error
* [x] Command-line interface
* [x] Custom time periodicity
* [x] Validate configuration values
* [ ] Get utilization statistics for the last X hours

Credits
=======

Inspired by [Amazon CloudWatch Monitoring Scripts for Linux](http://docs.aws.amazon.com/AmazonCloudWatch/latest/DeveloperGuide/mon-scripts-perl.html).

License
=======

MIT.
