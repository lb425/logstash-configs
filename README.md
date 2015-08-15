# logstash-configs
Usefull configs and patterns I thought I'd share

I'm sharing my logstash configs for anyone who is interested. Some background on my deployment, these configurations are deployed on a set of virtualized logstash servers in a cluster receiving around 1 billion log messages a day. They are written with speed and resource usage in mind. If my conditionals look weird please know that the logstash deployments are handling many different types of logs and I am only sharing the peices that I thought would be of most use.

I welcome feedback so if you think you know how the configs can be improved please let me know. If you think they're terrible I guess you can let me know that too.
