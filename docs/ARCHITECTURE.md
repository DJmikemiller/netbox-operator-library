# Project Architecture

## Overview

The NetBox Operator Library extends the official NetBox Community Device Type Library with telecom and ISP equipment.

The objective is to provide reusable, well-documented and modular definitions compatible with NetBox 4.x.

---

# Repository Structure

```text
custom/
├── manufacturers/
├── platforms/
├── device-roles/
├── device-types/
└── module-types/

docs/
examples/
reports/
scripts/
upstream/
```

---

# Design Principles

## Device Type

A Device Type represents a complete physical device.

Examples:

- Nokia 7750 SR-7
- Huawei NE20E-S2E
- Huawei MA5600T
- Nokia 7360 FX-8

Each chassis has its own YAML file.

Example:

```text
custom/device-types/Nokia/7750-SR-7.yaml
```

---

## Module Type

A Module Type represents a removable hardware component.

Examples:

- CPM
- IOM
- MDA
- PIC
- GPON board
- XGS-PON board
- PSU
- Fan Tray

Each module has its own YAML definition.

---

## Modular Equipment

Modular chassis should never contain fixed interface definitions when interfaces are provided by removable modules.

Instead:

- create Module Bays
- create Module Types
- install modules inside Module Bays

---

# Naming Convention

Manufacturers

Example

Nokia

Huawei

Cisco

Juniper Networks

---

Device Types

Use the official product name.

Examples

7750 SR-7

7450 ESS-1

NE20E-S2E

MA5600T

---

Module Types

Use vendor terminology whenever possible.

Examples

CPM

IOM

MDA

PIC

SCU

NCU

GPON

XGS-PON

---

# Documentation

Every Device Type should be based on official vendor documentation whenever available.

Preferred sources:

- Vendor documentation
- Hardware installation guide
- Product datasheet

---

# Compatibility

Target:

- NetBox 4.x
- NetBox Community Device Type Library

Whenever a Device Type already exists upstream, it should not be duplicated.

Only missing or enhanced definitions should be maintained in this repository.
