# 🖨️ Printer Not Printing

**Typical symptoms:** Job stuck in queue, printer shows offline, blank pages, error lights.

## Quick Checks
- [ ] Printer powered on, no error light, paper and ink/toner loaded
- [ ] Cable (USB/Ethernet) seated, or Wi-Fi connected to the same network as the PC
- [ ] Correct printer selected as the default

## Steps
1. **Check the queue:** Settings → Bluetooth & devices → Printers & scanners → select printer → *Open print queue*. Cancel any stuck jobs.
2. **Printer offline?** In the queue window, clear *Use Printer Offline* if ticked.
3. **Restart the Print Spooler:** `services.msc` → *Print Spooler* → Restart.
4. **Test connectivity (network printers):** `ping <printer-IP>`
5. **Reinstall / update the driver** from the manufacturer's site if the problem continues.
6. **Print a test page** from printer properties to confirm.

## Escalate If
Hardware fault (paper jam sensor, fuser, head), repeated driver failures across many PCs, or print server issues.

## Document
Printer model, IP, error shown, steps tried, final fix.
