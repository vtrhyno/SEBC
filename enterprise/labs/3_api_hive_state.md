```
Stop Hive Service
	curl -X POST -u vtrhyno:cloudera 'http://ec2-54-196-123-147.compute-1.amazonaws.com:7180/api/v1/clusters/vtrhyno/services/hive/commands/stop'	
Start Hive Service
	curl -X POST -u vtrhyno:cloudera 'http://ec2-54-196-123-147.compute-1.amazonaws.com:7180/api/v1/clusters/vtrhyno/services/hive/commands/start'

Check Hive Status
	curl -u vtrhyno:cloudera 'http://localhost:7180/api/v1/clusters/vtrhyno/services/hive'

Check Status of command #
	curl -u vtrhyno:cloudera 'http://localhost:7180/api/v1/commands/###'

```
