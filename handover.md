# VoltMart GRC Project - Executive Handover

## Overview
This document summarizes the governance, risk, and compliance (GRC) work completed for VoltMart: a full IT asset inventory, a STRIDE-based risk register, and an ISO 27001 control mapping with concrete mitigation actions.

## Asset Inventory Summary
16 IT assets were catalogued across workstations, payment devices, network equipment, and servers. Five assets were rated High sensitivity: the Back Office Laptop, the Backup External Hard Drive, both POS Terminals, and the Inventory Database Server. These five formed the basis of the risk assessment.

## Risk Heat-Map Summary

| Risk Level | Risk Score Range | Count | Example Risks |
|---|---|---|---|
| Critical | 15 | 3 | Database tampering, POS data interception (x2) |
| High | 10-12 | 3 | Ransomware on laptop, privilege escalation, backup exposure |
| Medium | 8 | 6 | Network spoofing, repudiation, server overload, backup corruption |

## Control Mapping Summary
All 12 identified risks were mapped to specific ISO 27001:2022 Annex A controls, each paired with a concrete, low-cost mitigation action realistic for a small retailer - such as enabling encryption on POS terminals, restricting privileged access, and setting up automated backups.

## Top 3 Priority Actions
1. **Enable end-to-end encryption on both POS terminals** (Risk Score 15) - protects live payment data, the single highest-impact risk identified.
2. **Restrict and log direct access to the inventory database** (Risk Score 15) - prevents undetected tampering with business-critical records.
3. **Set up automated backups for the back office laptop** (Risk Score 12) - ensures recovery capability against ransomware, which poses high impact to finance and payroll operations.

## Next Steps
VoltMart should implement the three priority actions above within 14-30 days, then review the full risk register and control mapping annually, or sooner if new systems are introduced.

## Related Files
- `assets.csv` - full IT asset inventory
- `risk_register.csv` - STRIDE-based risk assessment
- `control_mapping.csv` - ISO 27001 control mapping with mitigation actions