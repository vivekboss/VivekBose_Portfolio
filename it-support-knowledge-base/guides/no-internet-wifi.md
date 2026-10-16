# 🌐 No Internet / Wi-Fi Issues

Work from the bottom up: **physical → IP address → gateway → DNS → internet.**

## Steps
1. **Physical / Wi-Fi:** Cable plugged in? Link light on? Wi-Fi connected to the correct SSID? Airplane mode off?
2. **Scope the problem:** Do other devices have internet? If yes, the issue is likely local to this PC.
3. **Check IP configuration:** `ipconfig /all`
   - Address starting with `169.254.x.x` → DHCP failed (APIPA)
4. **Renew the IP:** `ipconfig /release` then `ipconfig /renew`
5. **Ping the gateway:** `ping <default-gateway>` – fails → local network/cable/switch/router issue
6. **Ping an external IP:** `ping 8.8.8.8` – works but websites don't load → DNS issue
7. **Flush DNS:** `ipconfig /flushdns`; check DNS server settings
8. **Network reset / adapter:** Disable and re-enable the adapter, update driver, or use *Network reset* in Windows settings.
9. **Check router/switch:** Reboot, verify lights, confirm DHCP is enabled.

## Escalate If
Multiple users affected, router/switch/ISP fault, or DHCP/DNS server problems.

## Document
Device, connection type, `ipconfig` findings, which ping tests failed, fix applied.
