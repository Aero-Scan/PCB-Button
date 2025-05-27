# AeroScan - Wireless Network Q&P Monitoring - PCB Button

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

## Overview

AeroScan is an IoT-based system designed to monitor the Quality and Performance (Q&P) of wireless network infrastructure. This project utilizes Raspberry Pi devices deployed across a site to collect real-time network metrics. These metrics are then sent to a central server for aggregation by Prometheus and visualization via Grafana dashboards, providing valuable insights into network health, helping to identify potential issues, and ensuring a reliable wireless experience.

The system features a central registration service (`pi-registrar`) for dynamic discovery of Raspberry Pi nodes by Prometheus. Configuration of the Raspberry Pis, including sensitive details like WiFi credentials and API keys, can be managed remotely using Ansible from the central server.


## Usage

*   **Ordering** Order PCB from a Pcb manufacturing and parts Through hole parts.
*   **Assembly** Assemble according to KiCAD designs.
*   **How Too** Attach button PCB to GPIO Pins on the PI and press both buttons at the same time to generate a new Unique Identifier.

## License

AeroScan is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

You are free to **share** (copy and redistribute the material in any medium or format) and **adapt** (remix, transform, and build upon the material) under the following terms:

*   **Attribution** — You must give [appropriate credit](https://creativecommons.org/licenses/by-nc-sa/4.0/#ref-appropriate-credit), provide a link to the license, and [indicate if changes were made](https://creativecommons.org/licenses/by-nc-sa/4.0/#ref-indicate-changes). You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
*   **NonCommercial** — You may not use the material for [commercial purposes](https://creativecommons.org/licenses/by-nc-sa/4.0/#ref-commercial-purposes).
*   **ShareAlike** - If you remix, transform, or build upon the material, you must distribute your contributions under the [same license](https://creativecommons.org/licenses/by-nc-sa/4.0/#ref-same-license) as the original.
*   **No additional restrictions** — You may not apply legal terms or [technological measures](https://creativecommons.org/licenses/by-nc-sa/4.0/#ref-technological-measures) that legally restrict others from doing anything the license permits.

For more information, see the [full license text](LICENSE) in this repository or visit:
[https://creativecommons.org/licenses/by-nc-sa/4.0/](https://creativecommons.org/licenses/by-nc-sa/4.0/)
