# OpenVPN Server

## K8s Host Patches

```bash
# Load module
modprobe iptable_raw

# Permanently
echo 'iptable_raw' > /etc/modules-load.d/iptables-raw.conf
```