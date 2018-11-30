## TODO: Make integration instead of agent check

## Beanstalk Datadog Agent Check ##

### Install ###
* Install prereqs through `sudo -u dd-agent /opt/datadog-agent/embedded/bin/pip install beanstalkc PyYAML`
* Put beanstalkd.py in /etc/datadog-agent/checks.d/
* Put beanstalkd.yml in /etc/datadog-agent/conf.d/
* Restart datadog-agent

### Dependencies ###

* [Beanstalkc](https://github.com/earl/beanstalkc)
* [PyYAML](http://pyyaml.org/)

### Datadog Docs ###
[Agent Checks](http://docs.datadoghq.com/guides/agent_checks/)

### Examples ###
This agent check is currently being used in production for [When I Work](http://wheniwork.com).
