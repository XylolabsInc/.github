<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/mark_dark.png" />
    <source media="(prefers-color-scheme: light)" srcset="assets/mark_light.png" />
    <img src="assets/mark_light.png" width="80" alt="Xylolabs" />
  </picture>
  <h1>Xylolabs Inc.</h1>
  <p><strong>Edge Physical AI that catches equipment faults and runs robots.</strong></p>
  <p>We build sensor hardware, edge AI and robot software for real industrial sites —<br/>port cranes, power plants, factories, battery charging areas and public spaces.</p>
  <br/>
  <img src="https://img.shields.io/badge/Edge-Physical_AI-3178c6?style=for-the-badge" alt="Edge Physical AI" />
  &nbsp;
  <img src="https://img.shields.io/badge/Equipment-Anomaly_Detection-00add8?style=for-the-badge" alt="Equipment anomaly detection" />
  &nbsp;
  <img src="https://img.shields.io/badge/Battery-Fire_Early_Warning-dea584?style=for-the-badge" alt="Battery fire early warning" />
  &nbsp;
  <img src="https://img.shields.io/badge/Robotics-On--device_AI-3572a5?style=for-the-badge" alt="Robotics" />
  <br/><br/>
  <img src="https://img.shields.io/badge/Rust-dea584?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Embassy-no__std-6e4c9e?style=flat-square" alt="Embassy" />
  <img src="https://img.shields.io/badge/Python-3572a5?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-61dafb?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Go-00add8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/vLLM-30a2ff?style=flat-square" alt="vLLM" />
  <br/><br/>
  <a href="https://xylolabs.com/en/"><img src="https://img.shields.io/badge/xylolabs.com-website-0d1117?style=flat-square&logo=safari&logoColor=white" alt="Website" /></a>
  <a href="https://xylolabs.com/en/contact/?type=poc"><img src="https://img.shields.io/badge/Request_a-PoC-0d1117?style=flat-square" alt="Request a PoC" /></a>
</div>

---

### Platforms

| Platform | What it does | Where it runs |
|----------|--------------|---------------|
| [**XyloZero**](https://xylolabs.com/en/solutions/xylo-zero/) | Reads sound, vibration, temperature, humidity and magnetic field together with PLC and drive data. Context Gating separates real anomaly events from normal load changes at the edge and turns them into inspection priorities. | Motors, gearboxes, conveyors, pumps, cranes, turbines, generators |
| [**Battery Fire Early Detection**](https://xylolabs.com/en/solutions/battery-early-warning/) | XyloZero sensor nodes with four built-in MEMS microphones and a main control box pick up the acoustic precursors of thermal runaway and estimate where they occurred. | AGV and AMR charging areas, electrified prime movers, ESS, battery packs |
| [**Autonomy & Robotics Platform**](https://xylolabs.com/en/solutions/robotics/) | On-device AI for robots and drones: SLAM navigation and autonomous patrols, VLA-based manipulation learning for robot arms, and autonomous port crane handling (in development). | Wheeled robots, drones, mobile manipulators, cobots, STS cranes |

### In the Field

| Sector | Work |
|--------|------|
| **Ports** | STS crane drivetrain condition monitoring at a major Korean container terminal — deployed and in operation |
| **Power** | Continuous acoustic monitoring pilot on coal-handling conveyors; predictive maintenance PoC for gas turbine generators |
| **Manufacturing & batteries** | Acoustic validation of battery fire precursors; condition monitoring PoC for shipyard welding equipment and cranes |
| **Public Physical AI** | 2026 on-device AI public service pilot with robots and drones; pine wilt diagnosis research with the National Institute of Forest Science |

Details: [case studies](https://xylolabs.com/en/case-studies/)

### What We've Been Building

- **Sensor hardware and firmware** — in-house multi-sensor boards (acoustic, vibration, environmental, UWB ranging) with Rust `no_std` firmware on Embassy, and battery-powered outdoor nodes with LTE-M1 uplink.
- **Xylolabs API** — a Rust (Axum + Tokio) platform that streams multichannel high-resolution audio and sensor data from edge devices, with transcoding, per-device sessions and operator and admin apps on web, iOS and Android.
- **Multimodal anomaly analysis** — open-weight multimodal LLMs served with vLLM review recorded sessions and file anomaly reports, next to a DCASE-based machine sound anomaly detection pipeline.
- **On-device robots** — service robots that run LLM and speech models on the robot's own accelerator instead of the cloud, plus audio-augmented VLA fine-tuning so manipulation policies can use what the robot hears.
- **Local model lab** — throughput and quality benchmarks for open-weight LLMs across Apple silicon, NVIDIA DGX Spark and H200, feeding our edge and server deployment choices.
- **[Knowledge Engine](https://github.com/XylolabsInc/Xylolabs-Knowledge-Engine)** (open source) — ingests Slack, Discord, Google Workspace and Notion into one searchable knowledge base with an AI bot on top.

### Company

Research began at Seoul National University in 2019; Xylolabs was incorporated in December 2025. We have a patent application filed for our multimodal data acquisition method for industrial anomaly detection.

**Programs:** MYSC EMA Original 2026 · BNK 2026 CHAIN-G · CMK Impactpreneur Cohort 14 · Shinhan BLUEWAVE Cohort 12 · MYSC Marine Accelerator Program

### Repositories

<!-- REPOS_START -->

| Repository | Description | Language |
|-----------|-------------|----------|
| [**.github**](https://github.com/XylolabsInc/.github) |  |  |
| [**Xylolabs-Knowledge-Engine**](https://github.com/XylolabsInc/Xylolabs-Knowledge-Engine) | Unified Knowledge Base Engine — continuously ingests Slack, Google Workspace, and Notion into a searchable AI-powered knowledge base with a Slack bot interface | `JavaScript` |

<!-- REPOS_END -->

### Organization Stats

<!-- STATS_START -->

| Metric | Value | Metric | Value |
|--------|-------|--------|-------|
| **Estimated LOC** | 6.6M | **Active days (1y)** | 366 |
| **Total Commits** | 27.6K | **Avg / week (90d)** | 1.0K |
| **Commits (30d)** | 7.4K | **Peak weekday** | Wed |
| **Contributors** | 3 | | |

#### Languages

![Language Bar](assets/langbar.svg)

![Languages](assets/languages.svg)

#### Activity (last 52 weeks)

![Activity Heatmap](assets/heatmap.svg)

<sub>Peak day: 2026-11-04 with 789 commits.</sub>

#### Weekly Activity Pattern

![Weekly Punch Card](assets/punchcard.svg)

<sub>Peak hour: Tue 16:00 KST (570 commits).</sub>

#### Contributor Insights

![Contributors](assets/contributors.svg)

<sub>Last updated: 2026-11-09</sub>
<!-- STATS_END -->

---

<div align="center">
  <a href="https://xylolabs.com/en/">xylolabs.com</a> · <a href="https://xylolabs.com/en/contact/">Contact</a>
</div>
