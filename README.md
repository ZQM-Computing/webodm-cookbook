# WebODM Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **WebODM cookbook** — drone imagery processing into maps and models. Not yet started in the Docker remainder on Node-1 and Node-3 (port target 18087 on Node-1, 18087 on Node-3). Patterns are planned from the design, not yet from verified runs. It is intended for Drone and imagery practitioners who turn photos into orthomosaics and elevation models. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** WebODM patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Drone and imagery practitioners who turn photos into orthomosaics and elevation models.

## Prerequisites

- WebODM via Docker Compose
- A drone image set you own
- Bash or PowerShell

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-project` | A first project: images in, orthomosaic out |
| 02 | `02-processing-nodes` | Processing nodes and task options |
| 03 | `03-outputs` | Orthomosaics, DEMs, and 3D models as deliverables |
| 04 | `04-cog-pairing` | Turning outputs into COGs for TiTiler serving (see titiler-cookbook) |

## Repository layout

```text
webodm-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [cog-cookbook](https://github.com/ZQM-Computing/cog-cookbook) — Cloud Optimized GeoTIFF creation, validation, TiTiler serving
- [titiler-cookbook](https://github.com/ZQM-Computing/titiler-cookbook) — Dynamic map tiles, STAC endpoints, cloud-native raster serving
- [geoserver-cookbook](https://github.com/ZQM-Computing/geoserver-cookbook) — Publishing, styling, federation, and securing OGC services
