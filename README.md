# signoz
signoz demo with docker-compose 

```bash
ansible-playbook up.yml
```

This does docker compose up on an "empty" signoz in a codespace. Use this as a starting point for instrumenting your app.

```bash
ansible-playbook down.yml
```

This does docker compose down on the clickhouse-setup/docker-compose-minimal.yaml (the same docker-compose file from up.yml)

The point of this branch was to test the hypothesis that signoz version 56 was to old to have an infrastructure dashboard. We updated to 0.73.0 and verified that the hypothesis was correct.


