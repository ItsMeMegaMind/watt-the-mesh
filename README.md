# ⚡ Watt-The-Mesh

> ⚠️ **WORK IN PROGRESS:** This hardware design and PCB layout are currently under active development. Schematics, footprints, and routing are subject to change before the first physical revision is fully tested and verified in the field.

---

**Watt-The-Mesh** is an open-source, ultra-range off-grid Meshtastic relay board. Designed to punch through long distances without dying on you in the field, it combines a high-efficiency power subsystem with a high-power 1W LoRa power amplifier.

### 🛠️ Hardware Specifications
* **MCU:** Nordic nRF52840 (Ultra-low power Bluetooth & System Controller)
* **RF Transceiver:** E22-900M30S (1W / +30dBm SX1262 LoRa module)
* **Power Management:** Integrated solar charging + high-efficiency TPS61022 boost converter for stable 5V delivery during 1W transmission bursts
* **Form Factor:** Compact, single-board design optimized for low EMI and off-grid mast deployment

### 🚧 Project Status
- [x] Power Subsystem & Boost Converter Layout (TPS61022)
- [ ] Solar Charger & Battery Management Integration
- [ ] nRF52840 & E22 Interconnect Routing
- [ ] Board Revision 1.0 Manufacturing & Bench Testing
- [ ] Outdoor Field Range & Solar Endurance Testing
