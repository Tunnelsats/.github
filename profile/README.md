<div align="center">
  <img src="https://github.com/Tunnelsats/tunnelsats/raw/main/images/brand/social/postman_ts_banner.jpeg" alt="TunnelSats Banner" width="100%" />
</div>

# Tunnel⚡Sats

**Hybrid connectivity for Lightning Nodes. No KYC. No Logs.**

TunnelSats provides pre-configured WireGuard VPN tunnels designed specifically for Bitcoin Lightning Node operators. We enable you to run your node in **Hybrid Mode** (Clearnet + Tor) to improve routing reliability and speed while keeping your home IP address private.

### ⚡ Key Features
* **Privacy First:** No KYC, no logs, local Curve25519 key generation, and payments via the Lightning Network only.
* **Hybrid Connectivity:** Hide your home IP behind our high-performance VPS endpoints while maintaining Tor `.onion` connectivity.
* **Fail-Closed Split-Tunneling:** Intelligent policy routing and kill-switch protection isolate Lightning P2P traffic (VPN) from host and LAN traffic.
* **Native Platform Integrations:** Dedicated apps and storefront packages for **Umbrel**, **StartOS**, and **myNode**, plus the managed `tunnelsats.sh` installer for **RaspiBlitz** and **bare-metal Linux** systems.
* **Global Reach:** Low-latency endpoints across Europe, North America, Asia, South America, and Oceania.

---

### 🛠️ Core Repositories

* **[Tunnelsats/tunnelsats](https://github.com/Tunnelsats/tunnelsats)** - Core CLI installer (`tunnelsats.sh`), fail-closed Managed Mode (`tunnelsats.slice` + `nftables` kill switch) for bare-metal Debian/Ubuntu, RaspiBlitz, and myNode, plus setup documentation.
* **[Tunnelsats/ts-umbrel-app](https://github.com/Tunnelsats/ts-umbrel-app)** - Native Dockerized TunnelSats app and Community App Store for **umbrelOS** (LND & Core Lightning) and Kubernetes (`k3s`).
* **[Tunnelsats/tunnelsats-startos](https://github.com/Tunnelsats/tunnelsats-startos)** - Native **StartOS** companion package with in-app Lightning storefront and in-container clearnet VPN routing (LND, Core Lightning & Eclair).
* **[Tunnelsats/ts-mynode](https://github.com/Tunnelsats/ts-mynode)** - Native **myNode BTC** application (App SDK v2), MyNode UI storefront, NIP-47 NWC auto-renewal, and managed dataplane integration.
* **[Tunnelsats/nostr-community-bot](https://github.com/Tunnelsats/nostr-community-bot)** - Modular TypeScript Nostr bot engine for NIP-17/NIP-59 E2EE DMs, Armada Concord V2 communities, and node diagnostics.
* **[Tunnelsats/upptime](https://github.com/Tunnelsats/upptime)** - Automated endpoint uptime and latency telemetry backing our network status dashboard.

---

### 🛟 Support & Community Hub

Need help configuring your node, testing clearnet reachability, or troubleshooting a tunnel? Visit our new **[Support & Community Service Page](https://tunnelsats.com/support)** on the homepage:
* **Encrypted Armada Nostr Community:** [tunnelsats.com/join-armada](https://tunnelsats.com/join-armada) (NIP-17 & Concord V2 encrypted support with zero phone/email required)
* **Telegram Support Group:** [tunnelsats.com/join-telegram](https://tunnelsats.com/join-telegram) (Real-time peer support and `@TunnelSatsBot` reachability checks)
* **Interactive Bot Diagnostics:** Run `/ping`, `/info`, `/tunnelsats`, and `/link` over Nostr or Telegram, plus step-by-step platform troubleshooting checklists on [tunnelsats.com/support](https://tunnelsats.com/support).

### 🔗 Resources

* **Website:** [tunnelsats.com](https://tunnelsats.com/) (Subscriptions, server discovery & dashboard)
* **Support & Service Hub:** [tunnelsats.com/support](https://tunnelsats.com/support) (Community channels, diagnostic bot & troubleshooting)
* **Setup Guide & FAQ:** [tunnelsats.com/guide](https://tunnelsats.com/guide) | [tunnelsats.com/faq](https://tunnelsats.com/faq)
* **System Status:** [tunnelsats.com/status](https://tunnelsats.com/status) (Real-time server uptime & latency metrics)
* **API Docs:** [api.tunnelsats.com](https://api.tunnelsats.com/) (Programmatic management, L402 & x402 agent endpoints)
* **Transparency & Warrant Canary:** [tunnelsats.com/transparency](https://tunnelsats.com/transparency)

---

<div align="center">
  <sub>Managed by the TunnelSats Team</sub>
</div>
