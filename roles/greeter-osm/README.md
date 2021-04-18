Role Name
=========

Deployment of [greeter-osm](https://github.com/osmcz/greeter-osm).

Requirements
------------

It was tested on RHEL 8. Pull request to make it work on other platforms are welcomed.

Role Variables
--------------

The variable and its defaults are:

```
username: login-to-osm
password: some-secret
greeter_location: /var/local/greeter-osm
statusfile: "{{greeter_location}}/statusgreeter"
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

  roles:
  - role: greeter-osm
    username: "osmcz-welcome"
    password: "{{ osmcz_welcome_password }}"

License
-------

WTFPL

Author Information
------------------

Miroslav Suchý <msuchy@redhat.com>
