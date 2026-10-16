# 🧾 POS Terminal Not Working

**Typical symptoms:** Terminal frozen, scanner/printer not responding, billing software won't open, transactions not syncing.

## Steps
1. **Isolate:** Whole terminal, or one peripheral (scanner, receipt printer, cash drawer, card machine)?
2. **Power & cables:** Check power, USB and network cables; reseat connections.
3. **Peripherals:** Test the scanner in Notepad (it should type the barcode). Print a test receipt.
4. **Restart** the POS application, then the terminal if needed (complete or park any open bills first).
5. **Network:** `ping` the server/gateway; check Wi-Fi/LAN link if transactions aren't syncing.
6. **Software:** Check for error messages, recent updates, disk space.
7. **Workaround:** Move the cashier to a spare terminal so customers aren't delayed.
8. **Vendor escalation:** Provide error text, screenshots, terminal ID and steps already tried.

## Receipt / Calculation Discrepancies
Compare the receipt against the POS transaction record, check item prices, discounts and tax settings, then trace the first point where totals diverge.

## Document
Terminal ID, symptom, downtime, root cause, vendor reference number.
