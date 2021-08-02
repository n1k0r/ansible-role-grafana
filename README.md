# Grafana role for Ansible

## Variables

```yaml
grafana:
  version: 8.0.6
  port: 3000
  user: user
  password: userpass
  plugins: grafana-clock-panel,grafana-simple-json-datasource
  source:
    host: 127.0.0.1
    port: 8086
    ssl: no
    token: N6qkeSx2JRV2tzfSaIR5suJuZ4fxjWRAuztT7mZq12ukesja7nEOFxDBn8kFajPah9Gth8WHxXk3eqZ8J45oYQ==
    org: default
    bucket: data
```

Account dictionary is also expected: https://gitlab.com/n1k0r-ansible/roles/master
