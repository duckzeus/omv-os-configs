# OMV OS Configs

Backup of OpenMediaVault server OS configuration files.

## Contents

- **omv/** — OMV config.xml and php.ini
- **ssh/** — sshd_config and ssh_config (no host keys)
- **nut/** — Network UPS Tools config (client mode to iMac)
- **clamav/** — ClamAV scanner config
- **monit/** — Monit service monitor config
- **fail2ban/** — Fail2ban jail configs (OMV-generated only)
- **cron/** — OMV cron job scripts
- **network/** — interfaces, hosts, hostname
- **system/** — fstab, enabled services list, installed packages
- **rsyslog/** — rsyslog config
- **docker/** — Docker daemon config

## Secrets Policy

No private keys, passwords, or  are tracked.
See  for excluded patterns.

## Additional Configs (v2)

- **apt/** — APT sources lists (OMV repos)
- **chrony/** — NTP time sync config
- **lvm/** — LVM config
- **mdadm/** — Software RAID config
- **smartd/** — Disk health monitoring
- **sysctl/** — Kernel parameters (OMV tuned)
- **docker/** — Docker daemon config
- **libvirt/** — VM management config
- **firewall/** — nftables and iptables rules
