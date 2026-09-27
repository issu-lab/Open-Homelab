![iSSU Open Homelab](assets/issu-open-homelab-banner.png)

**Built for my homelab. Shared with the community.**

iSSU Open Homelab is a collection of personal projects created to solve real needs in my home infrastructure.

These projects are designed, tested and improved through everyday use. Some are stable tools, while others are public experiments still under development.

The goal is simple: build practical solutions, document them clearly and share what may also be useful to others.

---

## Project Areas

### Home Automation

Interfaces, integrations and tools for managing the home through Home Assistant and related platforms.

### Networking

Documented and reusable network configurations, with a focus on segmentation, security and maintainability.

### Infrastructure

Projects for self-hosted services, virtualization, containers and homelab management.

### Automation

Tools that reduce repetitive work and connect different parts of the infrastructure.

### Shared Resources

Documentation, templates and common resources used across the iSSU ecosystem.

---

## Current Projects

### [VinylMatrix Card](https://github.com/issu-lab/vinylmatrix-card)

An animated turntable and cassette music card for Home Assistant.

VinylMatrix follows the active player from a configurable list and offers Minimal, Classic and Cassette styles in light and dark modes, with playback, volume and seeking controls when supported. Used regularly in Home Assistant without reported issues.

**Area:** Home Automation<br>
**Status:** Stable · 1.0.0<br>
**Distribution:** HACS custom repository · Dashboard card<br>
**Documentation:** Available

### [ThermoMatrix Card](https://github.com/issu-lab/thermomatrix-card)

A modular LCD-inspired climate card for Home Assistant.

ThermoMatrix provides a compact interface, visual configuration, responsive controls and support for different languages and themes.

**Area:** Home Automation  
**Status:** Active Development  
**Documentation:** In progress

### [ThermoPilot](https://github.com/issu-lab/thermopilot)

A native and configurable climate controller for Home Assistant.

ThermoPilot combines multiple environment sensors, presets and hardware commands in reusable thermostat instances, with optional dedicated power feedback for confirmed physical state and manual-operation detection.

**Area:** Home Automation<br>
**Status:** Active Development<br>
**Documentation:** Available

### [Energy Report](https://github.com/issu-lab/energy-report)

A native Home Assistant integration for resilient consumption accounting, monthly cost reports, forecasts and portable CSV archives.

Energy Report supports cumulative-energy sensors, instantaneous power sensors or both, while preserving its ledger across meter resets and replacements.

**Area:** Home Automation · Energy Management<br>
**Status:** Stable<br>
**Documentation:** Available

### [Load Manager](https://github.com/issu-lab/ha-load-manager)

An AppDaemon application for managing electrical loads through Home Assistant.

It monitors power usage and automatically controls configured devices, with photovoltaic support, notifications and MQTT discovery.

**Area:** Home Automation · Automation  
**Status:** Active Development  
**Documentation:** Available in Italian; revision planned

### [Matrix Home](https://github.com/issu-lab/matrix-home)

A self-hosted dashboard for personal services and homelab applications.

It provides a central interface for organizing and accessing services, with Docker deployment, multiple themes and optional authentication.

**Area:** Infrastructure  
**Status:** Active Development  
**Documentation:** Available in Italian; revision planned

### [i3 Matrix](https://github.com/issu-lab/i3-matrix)

A reproducible Matrix-inspired i3 desktop theme for local and remote sessions.

It packages the i3, i3blocks, Rofi, Picom, GTK and terminal configuration used
in the homelab, with automatic backups and checksum-verified installation of
the historical Matrix icon theme.

**Area:** Infrastructure · Shared Resources<br>
**Status:** Active Development<br>
**Documentation:** Available

### [IR Thermostat](https://github.com/issu-lab/ir-thermostat)

An archived AppDaemon climate controller for stateless infrared devices.

It uses power consumption as real-world feedback to verify commands, detect external operation and keep Home Assistant synchronized with the controlled device. It has been superseded by [ThermoPilot](https://github.com/issu-lab/thermopilot) and remains available for reference.

**Area:** Home Automation · Automation<br>
**Status:** Archived · Superseded by ThermoPilot<br>
**Documentation:** Historical reference

### MikroTik Network Framework

A modular and documented framework for managing MikroTik RouterOS configurations.

The project focuses on structured firewall rules, VLAN segmentation, routing policies and reusable configuration modules.

**Area:** Networking  
**Status:** Active Development  
**Availability:** Coming later

---

## Project Maturity

Projects can be public at any stage of development. Their current maturity is always stated clearly so that users know what to expect.

| Status | Meaning |
|---|---|
| 🟢 **Stable** | Used regularly and considered reliable for its documented purpose. |
| 🟡 **Active Development** | Used and actively developed. Features or configuration may change. |
| 🔵 **Experimental** | Published for development and testing. Not recommended for regular or production use. |
| ⚪ **Archived** | No longer actively maintained, but kept available for reference. |

A public repository does not automatically mean that a project is ready for everyday use. Experimental projects include a clear warning in their documentation.

---

## Principles

- Solve a real problem.
- Build for actual use.
- Keep the structure simple and reusable.
- Treat documentation as part of the project.
- Test changes in a real homelab.
- State limitations and maturity clearly.
- Improve projects gradually.

---

## Development Approach

Most projects begin as solutions for my own infrastructure.

They may be published early when a public repository is useful for testing, versioning or working across multiple systems. When this happens, the documentation clearly explains that the project is still experimental or under active development.

The priority is not to make every project appear finished. The priority is to make its current condition clear.

---

## License

Unless otherwise stated in an individual repository, projects in the iSSU Open Homelab ecosystem are released under the MIT License.
