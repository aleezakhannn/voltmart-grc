# VoltMart GRC Project

[

![Markdown Lint](https://github.com/aleezakhannn/voltmart-grc/actions/workflows/markdown-lint.yml/badge.svg)

](https://github.com/aleezakhannn/voltmart-grc/actions/workflows/markdown-lint.yml)

This repository contains the complete governance, risk, and compliance (GRC) project for VoltMart, including the IT asset inventory, a STRIDE-based risk register, an ISO 27001 control mapping, and an executive handover summary.

## Project Overview
This project followed a four-stage GRC process:
1. **Asset Inventory** - catalogued VoltMart's IT hardware, servers, and network assets
2. **Risk Register** - identified threats to high-sensitivity assets using the STRIDE framework, scoring each by likelihood and impact
3. **Control Mapping** - mapped each risk to a relevant ISO 27001:2022 Annex A control with a concrete mitigation action
4. **Executive Handover** - summarized findings and top priority actions for leadership

## Folder Structure
```text
voltmart-grc/
├── assets.csv              # IT asset inventory
├── risk_register.csv       # STRIDE-based risk assessment
├── control_mapping.csv     # ISO 27001 control mapping
├── handover.md              # Executive summary and priority actions
├── LICENSE                  # MIT License
└── README.md                 # This file
```

## Files
- [assets.csv](./assets.csv) - 16 IT assets with owners, business value, and sensitivity ratings
- [risk_register.csv](./risk_register.csv) - 12 risks mapped to STRIDE categories with calculated risk scores
- [control_mapping.csv](./control_mapping.csv) - ISO 27001 controls and mitigation actions for every risk
- [handover.md](./handover.md) - executive summary with risk heat-map and top 3 priority actions

## License
This project is licensed under the MIT License - see [LICENSE](./LICENSE) for details.