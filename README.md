# ⚡ 1-Click Self-Hosted n8n + Coolify + AI Agent VPS Starter Kit (2026 Edition)
[![Deploy on Contabo (24GB RAM Value)](https://img.shields.io/badge/Deploy%20on-Contabo%20VPS%20(Best%20RAM)-FFE500?style=for-the-badge&logo=linux&logoColor=black)](https://www.dpbolvw.net/click-101707955-15866558?sid=github_readme_contabo)
[![Deploy on Hostinger (1-Click hPanel)](https://img.shields.io/badge/Deploy%20on-Hostinger%20KVM-673AB7?style=for-the-badge&logo=hostinger&logoColor=white)](https://tonixai.pro/go/hostinger?sid=github_readme_hostinger)
[![Free RAM Calculator](https://img.shields.io/badge/Interactive-VPS%20Sizing%20Calculator-00E676?style=for-the-badge)](https://tonixai.pro/tools/n8n-calculator)

Run **unlimited 24/7 autonomous AI agents, n8n workflows, Open Claw, and Hermes Agent for ~$5–$12/mo**, eliminating $299+/mo Zapier & Make execution limits.

---

## 📊 1. Multi-Vendor VPS Hardware Benchmark (Tested on Live Workloads)

Before deploying, pick the server infrastructure that matches your technical style and RAM needs:

| Provider | Recommended Plan | RAM / vCPU | Deployment Method | Best For | Official Deal Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **🏆 Contabo** *(Toni's Live Server)* | **Cloud VPS 10 / VPS 8 NVMe** | **8 GB – 24 GB RAM** / 4–8 vCPU AMD EPYC | **Coolify 1-Click UI** or Docker Compose | Heavy AI Agents, Queue Mode, Ollama, Open Claw & Hermes (Maximum RAM/$) | [**Claim Contabo Deal ➔**](https://www.dpbolvw.net/click-101707955-15866558?sid=github_table_contabo) |
| **⚡ Hostinger** | **KVM 2 / KVM 4** | **8 GB – 16 GB RAM** / 2–4 vCPU | **Native hPanel 1-Click Template** | Beginners wanting zero Linux terminal setup (Code: `TONIXAI`) | [**Claim Hostinger Deal ➔**](https://tonixai.pro/go/hostinger?sid=github_table_hostinger) |
| **🔥 Hetzner** | **CX32 / CPX31** | **8 GB RAM** / 4 vCPU | Coolify 1-Click or Docker | European low-latency & fast single-core CPU | [**Compare Hetzner ➔**](https://tonixai.pro/go/hetzner?sid=github_table_hetzner) |
| **🚂 Railway** | **Hobby / Pro PaaS** | Dynamic RAM | Instant Template Deploy | Quick prototyping without managing a server | [**Deploy on Railway ➔**](https://tonixai.pro/go/railway?sid=github_table_railway) |

---

## 🚀 2. Two Zero-Headache Deployment Options

### Option A: The "Coolify Bridge" 1-Click Method (Turn Contabo/Hetzner into a No-Code UI)
Don't like managing raw Docker files? Install **Coolify** (free open-source PaaS) on your [Contabo VPS](https://www.dpbolvw.net/click-101707955-15866558?sid=github_coolify_contabo) with one command, then select **n8n with PostgreSQL** from the visual catalog:
```bash
curl -fsSL https://cdn.coollabs.io/coolify/install.sh | bash
```

### Option B: Direct Docker Compose Production Stack (`n8n` + `PostgreSQL` + `Redis`)
```bash
git clone https://github.com/tonixai/n8n-vps-starter-kit.git
cd n8n-vps-starter-kit
cp .env.example .env
docker compose up -d
```

---

## 🧰 3. Recommended Production Add-Ons (Pre-Configured in Templates)
To run production scraping and multi-account automation without hitting rate limits or IP blocks, our `.json` workflows integrate directly with:
1. **Scraping & Extraction Engine**: [Apify Community Node](https://tonixai.pro/go/apify?sid=github_stack) *(Bypass anti-bot protections on Google Maps, LinkedIn, & TikTok)*.
2. **Residential Proxy Guard**: [Proxy-Cheap / Bright Data](https://tonixai.pro/go/proxy?sid=github_stack) *(Prevent VPS IP blacklisting during 24/7 automation)*.
3. **SSL & Zero-Trust Tunnel**: [Cloudflare](https://cloudflare.com) *(Free HTTPS & DDoS protection for your webhook endpoints)*.

---

## 🧮 Need Help Sizing Your RAM?
Use our free interactive **[Multi-Vendor n8n Server Sizing Calculator](https://tonixai.pro/tools/n8n-calculator)** to test your workflow volume.

---
*Maintained by **Toni x AI Automation** (`tonixai.pro`). MIT License.*
