<p align="center"><img src="banner.jpg" width="100%" alt="Kernelmancer" /></p>

<p align="center"><i>Proxy cores · Network clients · Infrastructure — Go, Kotlin, Linux</i></p>

<p align="center">
  <a href="https://nemu-x.github.io/nemux-pages/"><img src="https://img.shields.io/badge/site-nemu--x.github.io-8E44AD?style=for-the-badge" alt="Site" /></a>
  <img src="https://img.shields.io/badge/Horde-7a0c0c?style=for-the-badge" alt="Horde" />
</p>

---

## 🛠️ Maintaining

| Project | What | Stack |
| --- | --- | --- |
| [**SlothClash**](https://github.com/Nemu-x/SlothClash) ⭐ 412 | Desktop Clash.Meta / mihomo client (fork of clash-verge-rev) — 77 PRs merged | Go · TypeScript |
| [**ClashFest**](https://github.com/Nemu-x/ClashFest) ⭐ 237 | Rule-based tunnel for Android (fork of ClashMetaForAndroid) — 190 PRs merged | Kotlin · Go |
| [**SwissKnife for MS Graph**](https://github.com/Nemu-x/SwissKnife-for-MS-Graph) | Cross-platform Microsoft 365 admin runtime: Graph, Exchange, Teams, on-prem AD; every change previewed and audited | Go |
| [**clash-companion**](https://github.com/Nemu-x/clash-companion) | LAN protocol + Go library to discover, pair with and remote-control mihomo clients. No cloud | Go |

## 🍊 Core work — [getmikan/Citrus](https://github.com/getmikan/Citrus)

Proxy core for [Mikan](https://github.com/Miroshka000/mikan) (mihomo fork) — **129 PRs merged**, plus patches to its `tls`, `utls` and `smux` forks.

- Relay under load: echo RTT **55–63 ms → 20 ms**
- Less memory per idle tunnel and fewer GC cycles / allocations per new connection
- Hysteria2 / TUIC / AnyTLS hot paths; fixed a TUIC CONNECT panic and a smux write race
- Benchmarks vs Xray-core, sing-box and mihomo; nightly perf check and `-race` job in CI

## ⚔️ Upstream

| Repo | Contribution |
| --- | --- |
| [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo/pulls?q=author%3ANemu-x) | **XHTTP transport for VLESS** — base transport, stream-up, download-settings, xmux `reuse-settings` (6 merged) |
| [clash-verge-rev](https://github.com/clash-verge-rev/clash-verge-rev/pulls?q=author%3ANemu-x) | Full Russian localization, incl. Windows installer |
| [PasarGuard/panel](https://github.com/PasarGuard/panel/pulls?q=author%3ANemu-x) | XHTTP in Clash Meta subscriptions, Hysteria2 SNI fix |
| [enfein/mieru](https://github.com/enfein/mieru/pulls?q=author%3ANemu-x) | ClashFest & SlothClash listed as official third-party clients |

## 🧰 Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,rust,kotlin,ts,js,python,php,vue,astro,godot&perline=10" alt="Languages" />
  <br/>
  <img src="https://skillicons.dev/icons?i=tauri,androidstudio,linux,ubuntu,bash,powershell,docker,githubactions,azure&perline=9" alt="Tools" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/mihomo-8E44AD?style=flat-square" alt="mihomo" />
  <img src="https://img.shields.io/badge/VLESS%20%2F%20XHTTP-8E44AD?style=flat-square" alt="VLESS / XHTTP" />
  <img src="https://img.shields.io/badge/Hysteria2-8E44AD?style=flat-square" alt="Hysteria2" />
  <img src="https://img.shields.io/badge/TUIC-8E44AD?style=flat-square" alt="TUIC" />
  <img src="https://img.shields.io/badge/AnyTLS-8E44AD?style=flat-square" alt="AnyTLS" />
  <img src="https://img.shields.io/badge/uTLS-8E44AD?style=flat-square" alt="uTLS" />
  <img src="https://img.shields.io/badge/OpenWrt-00B5E2?style=flat-square&logo=openwrt&logoColor=white" alt="OpenWrt" />
  <img src="https://img.shields.io/badge/ESXi-607078?style=flat-square&logo=vmware&logoColor=white" alt="ESXi" />
  <img src="https://img.shields.io/badge/Microsoft%20365%20%2F%20Entra-0078D4?style=flat-square" alt="Microsoft 365 / Entra" />
</p>

---

<p align="center">
  <img src="https://raw.githubusercontent.com/Nemu-x/Nemu-x/output/metrics.svg" alt="Metrics" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Nemu-x/Nemu-x/output/contrib-3d-dark.svg" />
    <img src="https://raw.githubusercontent.com/Nemu-x/Nemu-x/output/contrib-3d-light.svg" alt="3D contribution calendar" />
  </picture>
</p>

<p align="center">
  <img src="horde.png" height="28" style="vertical-align:middle;" />
  &nbsp;<b>Discipline above chaos. For the Horde. For uptime.</b>&nbsp;
  <img src="horde.png" height="28" style="vertical-align:middle;" />
</p>
