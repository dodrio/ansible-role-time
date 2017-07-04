# time

[![Build Status](https://travis-ci.org/m31271n/ansible-role-time.svg?branch=master)](https://travis-ci.org/m31271n/ansible-role-time)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-m31271n.time-blue.svg)](https://galaxy.ansible.com/m31271n/time)

Ansible role that setups time.

## Requirements

None.

## Role Variables

+ `time_timezone`: `Asia/Shanghai`
+ `time_local_rtc`: `0`
+ `time_ntp`: `true`

## Dependencies

None.

## Example Playbook

```
- hosts: servers
  roles:
    - role: m31271n.time
      time_timezone: Asia/Shanghai
```

* * *

<p align="center">Made with ❤ by <a href="http://index.m31271n.com">m31271n</a></p>
