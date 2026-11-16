# mr-alj.loc.cc // SRE Command Center

[![Domain](https://img.shields.io/badge/Domain-mr--alj.loc.cc-white?style=flat-square&logo=globe&logoColor=black)](https://mr-alj.loc.cc)
[![DNS](https://img.shields.io/badge/DNS-Anycast%20CNAME%20Flattening-111114?style=flat-square&logo=cloudflare&logoColor=white)](https://mr-alj.loc.cc)
[![Protocol](https://img.shields.io/badge/Security-TLS%201.3%20%2F%20HSTS-111114?style=flat-square&logo=letsencrypt&logoColor=white)](https://mr-alj.loc.cc)
[![Performance](https://img.shields.io/badge/Lighthouse-100%2F100-white?style=flat-square&logo=googlechrome&logoColor=black)](https://mr-alj.loc.cc)
[![Aesthetic](https://img.shields.io/badge/Theme-OLED%20Monochrome-000000?style=flat-square)](https://mr-alj.loc.cc)

High-availability personal infrastructure command center and engineering portal for **Alireza Jafarlou**, Site Reliability & Cloud Infrastructure Engineer.

---

## 🏛️ Architecture & Highlights

* **Global Anycast Edge:** Served globally via distributed edge caches with sub-50ms latency.
* **Zone Apex CNAME Flattening:** Deployed on a 100-year domain (`mr-alj.loc.cc`) using PowerDNS LUA records at the zone apex.
* **OLED Monochrome Design Language:** Pure pitch black (`#000000`) canvas engineered for contrast, modern minimalism, and zero runtime bloat.
* **Interactive SRE Shell:** Client-side bash terminal with persistent command history (`↑` / `↓`), responsive EndeavourOS hardware telemetry (`neofetch`), and system diagnostics.
* **Zero Runtime Overhead:** 100% pure vanilla HTML5, CSS3, and modern JavaScript. Zero bundlers, zero npm dependencies, and instantaneous initial paint.

---

## 📂 Repository Structure

```text
.
├── CNAME                  # Zone apex domain configuration (mr-alj.loc.cc)
├── ALJ-1x-b.jpg           # Official calligraphic monogram & brand asset
├── index.html             # SRE Command Center & interactive shell
├── health-api/
│   └── index.html         # Dedicated microservice spec & live REST console
└── README.md              # Infrastructure & deployment documentation
```

---

## 🛠️ Featured Systems & Submodules

### 1. [health-api](https://github.com/alirezajafarlou/health-api)
* **Live Specification & Console:** [mr-alj.loc.cc/health-api/](https://mr-alj.loc.cc/health-api/)
* **Stack:** Node.js, Express, PostgreSQL 16, Docker Compose, Jest CI
* **Highlights:** Hardened background polling engine with PostgreSQL persistence and strict RFC 1918 SSRF mitigation (blocks private IP ranges, loopback, and cloud metadata endpoints).

### 2. [Global Anycast Static Edge](https://mr-alj.loc.cc)
* **Stack:** GitHub Actions, PowerDNS LUA Flattening, Let's Encrypt TLS 1.3
* **Highlights:** Edge-cached static distribution with automated certificate lifecycle management and 100/100 Lighthouse performance.

---

## 🚀 Local Development

Since this repository contains pure zero-dependency static assets, test locally using any standard static file server:

```bash
# Clone the repository
git clone https://github.com/alirezajafarlou/alirezajafarlou.github.io.git
cd alirezajafarlou.github.io

# Start local server (Python 3)
python3 -m http.server 8000

# Open in browser
xdg-open http://localhost:8000
```

---

## 📬 Communication Channels

* **Domain:** [https://mr-alj.loc.cc](https://mr-alj.loc.cc)
* **GitHub:** [@alirezajafarlou](https://github.com/alirezajafarlou)
* **Telegram:** [@alirezajafarlouwork](https://t.me/alirezajafarlouwork)
* **LinkedIn:** [alirezajafarlou](https://linkedin.com/in/alirezajafarlou)
* **Email:** [alirezajafarlou.work@gmail.com](mailto:alirezajafarlou.work@gmail.com)

---

<p align="center">
  <sub>© 2026 Alireza Jafarlou • High-Availability Infrastructure Telemetry</sub>
</p>
