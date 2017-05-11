[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-logstash-config.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-logstash-config)
andrewrothstein.logstash-config
=========

Configures logstash for collecting logs from syslog and collectd and indexing with elasticsearch

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.logstash-config
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
