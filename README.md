README.md – LGPL Repository
# LGPL Source Code Repository

This repository provides the complete corresponding source code of LGPL-licensed software components used in Eloma devices, in accordance with the LGPL license terms.

## Purpose

To fulfill the obligations of the GNU Lesser General Public License (LGPL), this repository publishes the source code of libraries that are dynamically or statically linked within Eloma firmware releases. Each firmware version has a dedicated subdirectory containing the exact library versions used.

## Structure

```
lgpl-sources/
├── sw-9.41/
│   ├── libabc-2.1.0/
│   ├── libxyz-1.3.7-mod/
│   └── README.md
├── sw-9.48/
│   ├── libabc-2.2.0/
│   ├── libxyz-1.4.1/
│   └── README.md
└── sw-9.55/
    └── ...
```

## How to Use

1. Check the firmware/software version of your Eloma device.
2. Navigate to the corresponding subdirectory in this repository (e.g. `sw-9.48`).
3. Inside you will find the full source code of all LGPL components used in that firmware release, including license files and, if applicable, documentation of modifications.

## Legal Notice

Each library includes its original license and copyright information. Eloma does not claim authorship of these libraries. This repository is provided solely for the purpose of license compliance.

_Last updated: 2025-07-25_

