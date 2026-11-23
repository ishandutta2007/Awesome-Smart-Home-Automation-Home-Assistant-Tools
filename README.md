# Awesome-Smart-Home-Automation-Home-Assistant-Tools

# Top Smart Home Automation & Home Assistant Tools Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Home Assistant Ecosystem Tools, MCP AI Integrations, Local Automation Engines, Bridges & Custom Add-ons*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted smart home platforms** and **open-source GitHub projects** for **Smart Home Automation & Home Assistant Tools**. These tools extend Home Assistant and local-first smart homes with Model Context Protocol (MCP) AI agent control, HACS community add-ons, Zigbee/Z-Wave/Matter coordinators, Node-RED visual flows, Apple HomeKit bridges, and alternative open-source automation hubs.

**Examples** include Home Assistant Core, homeassistant-ai/ha-mcp, HACS, Homebridge, openHAB, Domoticz, Gladys Assistant, Node-RED, ioBroker, ESPHome, Zigbee2MQTT, Frigate NVR, Home Assistant Cloud (Nabu Casa), Hubitat Elevation, Samsung SmartThings, and Fibaro.

**Open-source emphasis**: This list heavily expands on active open-source Home Assistant companion tools, AI/MCP bridges, HACS integrations, custom firmware, and alternative self-hosted smart home hubs — ideal for Home Assistant power users, home-labbers, and developers building local-first, AI-enabled smart homes.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Home Assistant Cloud (Nabu Casa)](https://nabucasa.com)**  
  Official subscription service funding Home Assistant development, providing zero-config encrypted remote UI access, WebRTC camera streaming, and Google Assistant/Amazon Alexa voice bridges.

- **[Hubitat Elevation](https://hubitat.com)**  
  Hybrid local-first smart home hub with proprietary firmware and optional cloud remote-admin/backup subscriptions supporting Zigbee, Z-Wave, Matter, and LAN automations.

- **[Samsung SmartThings](https://smartthings.com)**  
  Cloud-connected smart home automation ecosystem integrating Matter, Thread, Zigbee, Z-Wave, and Samsung appliances with mobile routines.

- **[Fibaro (Nice Smart Home)](https://fibaro.com)**  
  Commercial Z-Wave and smart home automation platform offering Home Center gateways, cloud remote access, and scene controllers.

- **[Homey Pro / Homey Cloud (Athom)](https://homey.app)**  
  Commercial multi-protocol smart home hub and cloud automation service featuring visual Flow builders across Zigbee, Z-Wave, Matter, Thread, IR, and 433MHz.

- **[Tuya Smart / Smart Life](https://tuya.com)**  
  Cloud IoT platform and mobile app ecosystem powering millions of white-label Wi-Fi and Zigbee smart home devices.

- **[IFTTT (If This Then That)](https://ifttt.com)**  
  Cloud automation service connecting commercial smart home devices, voice assistants, webhooks, and web APIs through conditional applets.


## Open-Source GitHub Projects

- **[Home Assistant Core (home-assistant/core)](https://github.com)**  
  The premier open-source, local-first home automation platform written in Python with 3,000+ integrations, visual automation editors, Matter/Thread/Zigbee support, and energy management.

- **[Home Assistant MCP Server (homeassistant-ai/ha-mcp)](https://github.com)**  
  Official/community open-source Model Context Protocol (MCP) server connecting AI assistants (Claude, Cursor, VS Code, local LLMs) directly to Home Assistant entities, services, automations, and dashboards.

- **[HACS — Home Assistant Community Store (hacs/integration)](https://github.com)**  
  Essential open-source package manager for Home Assistant enabling one-click installation and updates for thousands of custom integrations, Lovelace cards, and themes.

- **[Node-RED (node-red/node-red)](https://github.com)**  
  Low-code, event-driven visual flow programming tool widely used alongside Home Assistant (`node-red-contrib-home-assistant-websocket`) for complex state-machine automations.

- **[Homebridge (homebridge/homebridge)](https://github.com)**  
  Lightweight open-source Node.js server that emulates the Apple HomeKit API, allowing thousands of non-HomeKit devices to be controlled natively via Apple Home and Siri.

- **[openHAB (openhab/openhab-core)](https://github.com)**  
  Vendor-agnostic open-source smart home automation server written in Java with semantic home modeling, Blockly/JS/Python rules, and extensive industrial/residential bindings.

- **[Domoticz (domoticz/domoticz)](https://github.com)**  
  Fast, lightweight open-source home automation system written in C++ engineered for low-resource SBCs with Lua, dzVents, and Python scripting.

- **[ioBroker (ioBroker/ioBroker.js-controller)](https://github.com)**  
  Modular Node.js smart home integration platform offering hundreds of protocol adapters (KNX, Modbus, Homematic, Zigbee) and visual rule editors.

- **[Gladys Assistant (GladysAssistant/Gladys)](https://github.com)**  
  Privacy-first, self-hosted open-source smart home software featuring clean built-in scenes, MQTT/Zigbee2MQTT support, and minimal YAML configuration.

- **[ESPHome (esphome/esphome)](https://github.com)**  
  Open-source YAML-driven firmware builder that turns ESP32, ESP8266, and RP2040 microcontrollers into native Home Assistant sensors, relays, and voice satellites.

- **[Zigbee2MQTT (Koenkk/zigbee2mqtt)](https://github.com)**  
  Open-source Zigbee-to-MQTT bridge supporting thousands of devices across dozens of vendors with an interactive mesh map and OTA firmware updates.

- **[Z-Wave JS UI (zwave-js/zwave-js-ui)](https://github.com)**  
  Open-source Z-Wave control panel and WebSocket/MQTT gateway powering Home Assistant's Z-Wave integration with full network diagnostics.

- **[Frigate NVR (blakeblackshear/frigate)](https://github.com)**  
  Open-source local AI NVR with real-time object detection and deep Home Assistant integration for instant camera snapshots, clips, and motion/person automation triggers.

### Additional Strong Open-Source Options

- **[AppDaemon (AppDaemon/appdaemon)](https://github.com)** & **[Pyscript (custom-components/pyscript)](https://github.com)** — Write stateful, event-driven Home Assistant automations in pure Python.
- **[Music Assistant (music-assistant/server)](https://github.com)** — Open-source whole-home multi-room audio manager integrated tightly with Home Assistant across Sonos, AirPlay, Chromecast, and Snapcast.
- **[Wyoming Protocol & Piper / Faster-Whisper / openWakeWord (rhasspy/wyoming)](https://github.com)** — Modular open-source local voice assistant pipeline enabling completely offline "Assist" voice control in Home Assistant.
- **[Tasmota (arendst/Tasmota)](https://github.com)** & **[WLED (Aircoookie/WLED)](https://github.com)** — Open-source ESP firmware for local MQTT/Home Assistant control of smart plugs, relays, and addressable LED lighting.
- **[Spook (frenck/spook)](https://github.com)** — Powerful open-source Home Assistant toolbox adding repair checks for broken entity references, extra service actions, and system diagnostics.
- **[Home Assistant OS & Supervised / Container Tools (home-assistant/operating-system)](https://github.com)** — Official minimal, appliance-like Linux OS built specifically to run Home Assistant and its add-on supervisor.

**Frameworks for building custom systems**: Combine **Home Assistant OS** + **HACS** + **Zigbee2MQTT** + **ESPHome** for core device control, add **Node-RED** or **Pyscript** for advanced logic, and connect **homeassistant-ai/ha-mcp** with **Ollama** or **Claude** for natural-language smart home management.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AI/MCP bridges (`homeassistant-ai/ha-mcp`) grant LLMs the ability to inspect entity states and invoke Home Assistant service calls (such as unlocking doors, toggling switches, or running scripts); always use scoped long-lived access tokens and restrict exposed domains in production.
- Isolate smart home hubs and IoT devices on a dedicated VLAN without unrestricted WAN access, and use WireGuard/Tailscale or Nabu Casa for encrypted remote connectivity.

---

**Made for Home Assistant power users, smart home builders, home-labbers, and open-source developers.**  
Let's make smart home automation local-first, intelligent, private, and open to everyone.
