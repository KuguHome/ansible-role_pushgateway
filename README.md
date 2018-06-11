# ansible-role-pushgateway

Installs the pushgateway for Prometheus.

# Requirements

None

# Role Variables

| Variable | Description | Default |
|----------|-------------|---------|
| `pushgateway_version`| Version of the pushgateway to use | `0.5.1` |
| `pushgateway_web_listen_address`| Network address to listen on ( --web.listen-address ) | `localhost:9091` |

# Dependencies

None

# Example Playbook

    - hosts: all
      roles:
        - { role: kuguhome.pushgateway }

# License

MIT

Author Information
------------------

https://github.com/kuguhome/
