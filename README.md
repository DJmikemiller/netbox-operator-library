# NetBox Operator Library

[![NetBox](https://img.shields.io/badge/NetBox-4.x-blue)](https://netbox.dev/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Overview

**NetBox Operator Library** is an extension of the official **NetBox Community Device Type Library** dedicated to Internet Service Providers (ISP), telecom operators and enterprise networks.

The objective is to provide a complete and well-documented library of:

- Device Types
- Module Types
- Manufacturers
- Platforms
- Device Roles

for networking, optical transport, access and power infrastructure.

Whenever possible, this project reuses the official NetBox Community Device Type Library and only adds missing or operator-specific equipment.

---

## Supported Vendors

Current scope includes:

- Nokia
- Huawei
- Cisco
- Juniper
- Ceragon
- ADVA / Adtran
- Telco Systems
- Vertiv
- Eltek

Additional vendors may be added in the future.

---

## Repository Structure

```text
netbox-operator-library/
│
├── .github/
│
├── custom/
│   ├── manufacturers/
│   ├── platforms/
│   ├── device-roles/
│   ├── device-types/
│   └── module-types/
│
├── docs/
│
├── reports/
│
├── scripts/
│
├── upstream/
│
├── .gitignore
└── README.md
```

---

## Project Goals

The project has four main objectives:

- Extend the official NetBox Device Type Library.
- Create missing telecom device definitions.
- Model modular chassis and removable modules.
- Provide documentation and automation tools.

---

## Equipment Families

### IP/MPLS

- Nokia 7210 SAS
- Nokia 7250 IXR
- Nokia 7450 ESS
- Nokia 7750 SR
- Huawei NE20E
- Huawei NE8000
- Cisco Catalyst
- Juniper ERX

### Access

- Nokia 7360 ISAM FX
- Huawei MA5600T
- Huawei MA5800
- Huawei SmartAX C200

### Microwave

- Ceragon IP-10
- Ceragon IP-20
- Alcatel-Lucent 9400 AWY

### Carrier Ethernet

- ADVA / Adtran
- Telco Systems

### Power Systems

- Vertiv
- Eltek

---

## Project Roadmap

See:

- docs/ROADMAP.md

---

## Documentation

Project documentation is available under:

```text
docs/
```

Technical documentation will include:

- chassis architecture
- module compatibility
- slot layout
- power modules
- cooling modules

---

## Automation

Python tools will be developed to:

- synchronize the official NetBox Device Type Library
- audit equipment inventories
- generate YAML templates
- validate YAML files
- import into NetBox

---

## Compatibility

Designed for:

- NetBox 4.x
- NetBox Community Device Type Library

---

## References

Official NetBox Community Device Type Library

https://github.com/netbox-community/devicetype-library

NetBox Project

https://github.com/netbox-community/netbox

---

## Contributing

Contributions are welcome.

Please read:

- docs/CONTRIBUTING.md

before submitting pull requests.

---

## License

MIT License
