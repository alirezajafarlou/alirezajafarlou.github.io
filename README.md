# mr-alj.is-a.dev // DevOps Command Center

[![Domain](https://img.shields.io/badge/Domain-mr--alj.is--a.dev-white?style=flat-square&logo=globe&logoColor=black)](https://mr-alj.is-a.dev)
[![DNS](https://img.shields.io/badge/DNS-Cloudflare%20Anycast-111114?style=flat-square&logo=cloudflare&logoColor=white)](https://mr-alj.is-a.dev)
[![Security](https://img.shields.io/badge/Security-TLS%201.3%20%2F%20Auto%20ACME-111114?style=flat-square&logo=letsencrypt&logoColor=white)](https://mr-alj.is-a.dev)
[![Performance](https://img.shields.io/badge/Lighthouse-100%2F100-white?style=flat-square&logo=googlechrome&logoColor=black)](https://mr-alj.is-a.dev)
[![Aesthetic](https://img.shields.io/badge/Theme-OLED%20Monochrome-000000?style=flat-square)](https://mr-alj.is-a.dev)

High-availability personal infrastructure portal and engineering command deck for **Alireza Jafarlou**, DevOps & Cloud Infrastructure Engineer.

---

## 🏛️ Architecture & Highlights

* **GitOps Edge Delivery:** Automated continuous deployment directly from Git push to worldwide Fastly/GitHub edge nodes with sub-30ms global latency.
* **Automated Cloudflare DNS:** Configured upstream via open-source PR `#61608` on `is-a-dev/register` targeting `alirezajafarlou.github.io`.
* **OLED Monochrome Design Language:** Pure pitch black (`#000000`) canvas engineered for maximum contrast, modern minimalism, and zero visual bloat.
* **Interactive DevOps Shell:** Client-side terminal with persistent command history (`↑` / `↓`), simulated container fleet diagnostics (`docker-ps`), multi-stage CI/CD inspection (`pipeline`), and host telemetry (`fastfetch`).
* **Zero Runtime Overhead:** 100% pure vanilla HTML5, CSS3, and modern JavaScript. Zero bundlers, zero npm dependencies, and instantaneous initial paint.

---

## 📂 Repository Structure

```text
.
├── CNAME                  # Custom domain configuration (mr-alj.is-a.dev)
├── ALJ-1x-b.jpg           # Official calligraphic monogram & brand asset
├── index.html             # DevOps Command Center & interactive shell
├── health-api/
│   └── index.html         # Dedicated microservice spec & live REST console
└── README.md              # Infrastructure & deployment documentation
```

---

## 🛠️ Featured Systems & Submodules

### [health-api](https://github.com/alirezajafarlou/health-api)
* **Live Specification & Console:** [mr-alj.is-a.dev/health-api/](https://mr-alj.is-a.dev/health-api/)
* **Stack:** Node.js, Express, PostgreSQL 16, Docker Compose, Jest CI
* **Highlights:** Hardened background polling engine with PostgreSQL persistence and strict RFC 1918 SSRF mitigation (blocks private IP ranges, loopback, and cloud metadata endpoints).

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

* **Domain:** [https://mr-alj.is-a.dev](https://mr-alj.is-a.dev)
* **GitHub:** [@alirezajafarlou](https://github.com/alirezajafarlou)
* **Telegram:** [@alirezajafarlouwork](https://t.me/alirezajafarlouwork)
* **LinkedIn:** [alirezajafarlou](https://linkedin.com/in/alirezajafarlou)
* **Email:** [alirezajafarlou.work@gmail.com](mailto:alirezajafarlou.work@gmail.com)
* **Phone:** [+98 922 8358 243](tel:+989228358243)

---

<p align="center">
  <sub>© 2026 Alireza Jafarlou • DevOps & Infrastructure Automation</sub>
</p>
