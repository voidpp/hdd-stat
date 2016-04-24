About
--
Microservice and cli tool for get info about hdds.

Install
--
```bash
pip install hdd-stat
```

Usage
--
CLI:
```bash
$ hdd-stat
```
uWSGI example config:
```ini
[uwsgi]
processes = 2
module = hdd_stat.app:app
http-socket = :8090
```
