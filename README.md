boundary-http-stressd
=====================

Daemon that hits load balancer

Install
--------

```bash
$ rpm -ivh https://github.com/jdgwartney/boundary-http-stressd/releases/download/RE-01.00.00/boundary-http-stressd-01.00.00-1.noarch.rpm
```
Help
----
```bash
$ http-stress -h
http-stress [-c concurrency] [-d] [-r requests] [-u url] [-s sleep] -v
where:
  concurrency - number of connections, default 10
  daemon      - run in daemon mode, default 0
  requests    - number of requests per connection, default 10
  sleep       - delay between invocations, default 5
  url         - endpoint to contact, default http://localhost/
```

Daemon
------
```bash
$ /etc/init.d/http-stressd
Usage: /etc/init.d/http-stressd {start|stop|status|restart}
```
