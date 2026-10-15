# Samba audit ruleset

Install these files on the Wazuh manager. Keep each filename as it is in this folder.

| File | Wazuh install path |
| --- | --- |
| `samba_audit_decoders.xml` | `/var/ossec/etc/decoders/samba_audit_decoders.xml` |
| `samba_audit_rules.xml` | `/var/ossec/etc/rules/samba_audit_rules.xml` |

After the files are in place, restart the manager:

```
systemctl restart wazuh-manager
```
