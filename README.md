# Ansible Role For NTP

An Ansible Role that installs NTP on RHEL/CentOS, Debian/Ubuntu.

## Role Variables

Default values for variables are listed in (`defaults/main.yml`).
Here is a list of available variables.

[**for RHEL/CentOS**]
   
  `service_name: chronyd`

[**for Debian**]
   
   `service_name: ntp`

### Default values:- 

`ntp_enabled: true`

`ntp_timezone: Africa/Cairo`





