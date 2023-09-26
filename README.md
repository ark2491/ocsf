# ocsf
This repository is the starting point for Splunk TA's that compliment the OCSF Schema.

1. TA-linux-auditd-oscf
  - To perform testing, I actually changed the sourcetype name to differentiate it from other logs on my at home splunk. This does not have to be permanent. Ideally, I would like to build on top of the content created in [TA-linux_auditd](https://github.com/doksu/splunk_auditd), this was just for me to differentiate while working on my home lab
  - Current Version 1.0.1 ties to OCSF class_uid's [1001, 1005, 1007, 2001, 3001, 3002, 3003](https://schema.ocsf.io/), with more to be integrated
