# [Catena](https://github.com/alysoid/catena) Ansible Role: timezone

Manage system timezone with systemd using `timedatectl`.

## Role default variables

For a list of all available timezones, use the command `timedatectl list-timezones` or [check here available timezones](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones).

| Variable   | Default | Info                                                   |
| ---------- | ------- | ------------------------------------------------------ |
| `timezone` | Etc/UTC | System timezone. Default to Coordinated Universal Time |
