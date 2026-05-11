# Hi, I'm Andrew 👋

**Technical Lead | SRE & AI @ BMO** | Building reliable systems at scale | AI-Augmented Development

## 🚀 Recent Work

Building infrastructure and tools across IoT, observability, and community data — most of it AI-augmented:

- **Ottawa River freshet case file** — community-built flood-monitoring stack for the Ottawa River watershed (k3s, TimescaleDB, PostgREST, static HTML dashboard at freshet.xgrunt.com). Statistical case file documenting a post-2017 regime change in spring flood peaks at Lac Coulonge: nine illustrated exhibits, four statistical tests, daily AI-generated plain-language briefs, calibrated seasonal probability forecast. Public, reproducible, falsifiable.
- **Multi-camera surveillance system** with Raspberry Pi cameras, HLS streaming, MQTT integration, and web UI
- **LoRa sensor network** with ESP32-S3 nodes → LoRa gateway → MQTT → InfluxDB for long-range monitoring
- **Temperature monitoring** with 4 deployed ESP8266 sensors → InfluxDB → Grafana

**What I learned:** AI tools (Claude Code, Claude Pro, GitHub Copilot, Cline) are force multipliers for infrastructure work — I focused on architecture, security, and reliability while AI handled implementation details. The freshet project pushed this further: the AI is also doing daily ingest agent work, plain-language synthesis of technical telemetry, and analytical scripting against historical hydrometric records.

## 🛠️ Tech Stack

**SRE/DevOps:** Terraform · Terragrunt · AWS CDK · Kubernetes (k3s, EKS) · Docker · Dynatrace · Grafana · Prometheus · GitHub Actions
**Cloud:** AWS · Azure · GCP · OpenStack · OpenNebula · Cloudflare Tunnel
**Databases:** Postgres · TimescaleDB · PostgREST · InfluxDB · Cassandra · Oracle · MariaDB
**IoT/Embedded:** ESP32-S3 · ESP8266 · Raspberry Pi · LoRa · MQTT · C/C++ · PlatformIO · Arduino
**Languages:** Python · Bash · C/C++ · Java · JavaScript
**AI Tools:** Claude Code · Claude Pro · GitHub Copilot · Cline · Anthropic API (scheduled agent routines)

## 📌 Featured Projects

### [🌊 Ottawa River Freshet — community flood monitoring + case file](https://github.com/aachtenberg/ottawa-river-freshet)
Community-built flood-monitoring stack for the Ottawa River watershed, driven by a real-world need: documenting and statistically testing a post-2017 regime change in spring flood peaks at Lac Coulonge, Quebec. Live dashboard at [freshet.xgrunt.com](https://freshet.xgrunt.com) aggregating Hydro-Québec, ECCC, MVCA, and Quebec Vigilance telemetry into a single TimescaleDB / PostgREST stack on a homelab k3s cluster. Case file includes nine illustrated exhibits (newspaper-style HTML/SVG infographics), four statistical tests (regime-change detection, climate-forcing regression, annual basin volume integration, freshet-shape analysis), a daily AI-generated plain-language brief written by a scheduled Claude agent, and a calibrated seasonal probability forecast (Gaussian-kernel analog matching with post-2017 era weighting). Built to be public, reproducible, opinionated, and falsifiable.

**Tech:** TimescaleDB · PostgREST · k3s · Cloudflare Tunnel · Python (stdlib only) · Static HTML/SVG · Chart.js · GitHub Actions (auto-mirror) · Anthropic Claude routines · puppeteer (PNG render)

### [📹 Raspberry Pi Camera Control](https://github.com/aachtenberg/raspberry-pi-camera-control)
Multi-camera surveillance system with web UI, dual streaming modes (HLS/VLC), and MQTT integration. Hardware H.264 encoding with ffmpeg, real-time settings control, and system monitoring.

**Tech:** Python · Raspberry Pi · HLS · MQTT · ffmpeg · Flask · Hardware H.264

### [📡 ESP32 LoRa Sensor Network](https://github.com/aachtenberg/esp32-lora-sensor)
Long-range wireless sensor network with ESP32-S3 LoRa nodes and gateway. BME280 sensors monitor temperature, humidity, and pressure with MQTT bridge for cloud integration.

**Tech:** ESP32-S3 · LoRa · MQTT · BME280 · C++ · PlatformIO

### [🌡️ ESP8266 Temperature Monitoring](https://github.com/aachtenberg/esp12f_ds18b20_temp_sensor)
Production IoT system with 4 deployed sensors. C++ firmware with WiFi fallback, InfluxDB integration, and proper secrets management.

**Tech:** ESP8266 · C++ · PlatformIO · InfluxDB · DS18B20 · WiFi

### [🥧 Raspberry Pi Docker Infrastructure](https://github.com/aachtenberg/raspberry-pi-docker)
Production self-hosted stack: InfluxDB, Grafana, Home Assistant, Prometheus, Nginx Proxy Manager, Cloudflare Tunnels.

**Tech:** Docker · InfluxDB · Grafana · Prometheus · Nginx · Cloudflare · Raspberry Pi

## 💼 Experience Highlights

- **BMO** - SRE Technical Lead (2023-Present)
  - High-availability systems design and AI-augmented development practices

- **BlackBerry** - Senior Technical Manager (2013-2019)
  - Led Enterprise Cloud & Data Platforms across AWS, Azure, and private clouds

- **BlackBerry** - Senior Software Developer (2010-2012)
  - Scaled BBM infrastructure to 100M+ users across distributed data centers

- **Research In Motion** - Infrastructure Engineering Specialist (2007-2010)
  - SME for BBM infrastructure and massively distributed cloud systems

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Andrew_Achtenberg-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/aachtenberg/)

---

💡 *Always learning, always building. Currently exploring AI's role in SRE practices — and in community-data work where the stakes are real and the audience is actual neighbours.*
