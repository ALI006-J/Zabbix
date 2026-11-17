# Zabbix Monitoring

This repository stores the version-controlled Zabbix monitoring templates, dashboards, and supporting configuration files.

## Sophos XGS3300

The Sophos XGS3300 configuration files are maintained as separate versions so that a user-confirmed importable baseline is not overwritten by an experimental dashboard redesign.

Planned file roles:
- `Sophos_XGS3300_Zabbix8_Complete_FINAL.yaml` — original baseline.
- `Sophos_XGS3300_Zabbix8_Complete_DASHBOARD_FIX1.yaml` — last version reported as successfully imported into Zabbix.
- `Sophos_XGS3300_Zabbix8_Complete_DASHBOARD_REDESIGNED.yaml` — experimental redesign; not yet verified by a live Zabbix import.

**Rule:** Do not replace the agreed dashboard layout or promote an experimental YAML file to the baseline without explicit user approval and an import check in the target Zabbix instance.
