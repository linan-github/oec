# OPSGENIE EDGE CONNECTOR
Forked from https://github.com/opsgenie/oec to add config for log file path

## Configuration
### Logs
OEC default log file is located:

* On Windows: `var/log/opsgenie/oec<pid>.log`
* On Linux: `/var/log/opsgenie/oec<pid>.log`
* At the end of the file name of the log, there is program identifier (pid) to identify which process is running.

* Set `OEC_CONF_LOG_FILE_PATH` to specify log file path
