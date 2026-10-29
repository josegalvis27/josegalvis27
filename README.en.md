<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f766e,50:5b21b6,100:a21caf&height=220&section=header&text=Jos%C3%A9%20Galvis&fontSize=64&fontColor=ffffff&fontAlignY=38&desc=Computer%20Engineer%20%C2%B7%20CTO%20at%20Coco%20Wallet%20%26%20Coco%20Mercado&descAlignY=58&descSize=18&animation=fadeIn" width="100%" alt="José Galvis" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=5EEAD4&center=true&vCenter=true&width=640&lines=CTO+at+Coco+Wallet+%26+Coco+Mercado;Co-founder+at+Staff+On;Fintech+%C2%B7+Web3+%C2%B7+Flutter;Teams+that+work+with+AI+agents" alt="CTO at Coco Wallet & Coco Mercado" />

<br/>

<a href="https://josegalvis.vercel.app"><img src="https://img.shields.io/badge/🌐_Portfolio-7C3AED?style=for-the-badge" alt="Portfolio" /></a>
<a href="https://josegalvis.vercel.app/cv/en"><img src="https://img.shields.io/badge/📄_View_my_resume-0F766E?style=for-the-badge" alt="Resume" /></a>
<a href="https://linkedin.com/in/josegalvisrivas"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:jose.galvis.rivas@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://x.com/josegalvis27"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>

<br/><br/>

[🇪🇸 Español](./README.md) · **🇺🇸 English**

</div>

---

### 👋 About me

I'm a **Computer Engineer** from Caracas, Venezuela 🇻🇪. Since 2022 I've been **CTO of [Coco Wallet](https://cocowallet.app) and Coco Mercado**, a self-custodial dollar wallet with fiat ramps in 9 countries across the Americas and Europe, and I'm **co-founder of [Staff On](https://staffon.app)**, a temporary event staffing marketplace.

<table>
  <tr>
    <td align="center"><h3>190K+</h3><sub>registered users</sub></td>
    <td align="center"><h3>US$75M+</h3><sub>moved through fiat ramps</sub></td>
    <td align="center"><h3>4×</h3><sub>monthly operations in 2 years</sub></td>
    <td align="center"><h3>500+</h3><sub>merged PRs in the wallet</sub></td>
  </tr>
</table>

I own architecture, mobile (Flutter), payments, security and releases with a team of 3 engineers and 3 QA.

### 🎯 Case studies

| | Problem → Solution → Result |
|---|---|
| 🔐 **MPC with zero loss** | The wallet relied on seed phrases → integrated MPC/TSS (Particle) into the Flutter app and led the migration → **3,500+ funded users migrated, zero loss of funds** |
| ⚡ **Sends that don't fail** | A share of ERC-4337 sends were failing → traced the root cause (UserOp nonce) and moved it client-side → **−83% send failures** and **−64% gas** per transaction |
| 💸 **Cheaper infrastructure** | US$80/day on RPC → diagnosed a miscalibrated deposit monitor → **−75% cost (~US$22K a year)** while operations grew 4× |
| 💳 **10+ payment rails** | Bridge, Ripio, Pago Móvil, Bizum, Zelle, PayPal, Stripe, Ramp and KYC with Sumsub, across 9 markets |

### 🚀 Projects

| Project | What it is | Links |
|---|---|---|
| 🎰 **Millo** | On-chain lottery inside Coco Wallet on Megapot (Base): gasless USDC tickets and a daily draw | [Demo](https://megapot-three.vercel.app) · [Code](https://github.com/josegalvis27/millo) |
| ✈️ **Rumbo** | Travel mini app for Coco Wallet: flights, stays and tours paid in USDC | [Code](https://github.com/josegalvis27/rumbo) |
| 🧑‍💼 **Staff On** | Verified event staffing marketplace in Caracas: Flutter app, Node.js API and dashboard. I'm co-founder | [staffon.app](https://staffon.app) |
| 🗳️ **Quórum** | Verifiable voting with ZK proofs (Semaphore v4) anchored on Base · Platanus Hack 26 | [Demo](https://quorum-sefw.onrender.com) · [Code](https://github.com/platanus-hack/platanus-hack-26-ve-team-3) |
| 🏋️ **José Fit** | Workout PWA that works offline at the gym | [Demo](https://jose-fit.vercel.app) · [Code](https://github.com/josegalvis27/jose-fit) |
| 🕹️ **Caracas arcade** | 5 Phaser 3 games: ¡Trompazo!, ¡Hay Puesto!, Metro ¡Hora Pico! and more | [Code](https://github.com/josegalvis27/arcade-caraqueno) |
| 🛒 **amazon-deal-bot** | Deal alerts on Telegram with Cloudflare Workers + D1 | [Code](https://github.com/josegalvis27/amazon-deal-bot) |
| 📊 **bcv-tasas** | Official Venezuelan Central Bank rates straight into SAP Business One, in under 10 seconds | [Code](https://github.com/josegalvis27/bcv-tasas) |
| 🎁 **Mi Amigo Secreto** | Secret Santa organizer | [Code](https://github.com/josegalvis27/mi-amigo-secreto) |
| 📺 **CACO TV** | Minimal Android TV launcher in Kotlin + Compose | — |
| 🧠 **SmartTask AI** | macOS task calendar with a Gemini assistant | [Code](https://github.com/josegalvis27/smartTaskAI) |

### 🤖 AI Engineering

| | |
|---|---|
| 🏢 **Agent office** | One Claude Code engine per person, a shared queue and human approval: agents propose, people approve |
| 🧪 **Implementation graph** | 10 agents that take a feature from spec to green tests and E2E, with adversarial audits |
| 🎬 **Video studio** | 4K tutorials for 10 countries from real app screens and a cloned voice |

### ⚙️ CI/CD · GitHub Actions

Pipelines I built for Coco Wallet:

| Workflow | What it does |
|---|---|
| 📦 **Build & Notify QA** | On every merge to `develop` it computes the build via the App Store Connect API, builds signed APK and IPA and notifies QA |
| 🤖 **Claude Fix QA Bug** | QA comments on an issue → Claude Code fixes the bug on the right branch, opens the PR and links it to the issue |
| 🖼️ **Update Goldens** | Regenerates golden tests on Linux like CI and commits them to the PR branch |
| 🔑 **Check iOS Credentials** | Every Monday checks the `.p12` and provisioning profile and warns 30 days before they expire |

### 🛠️ Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=flutter,dart,kotlin,ts,js,nodejs,nextjs,react,python&theme=dark" alt="Languages and frameworks" /><br/>
  <img src="https://skillicons.dev/icons?i=aws,cloudflare,mongodb,supabase,firebase,solidity,githubactions,figma,vercel&theme=dark" alt="Cloud and tools" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ERC--4337-6D28D9?style=flat-square" />
  <img src="https://img.shields.io/badge/MPC%2FTSS-6D28D9?style=flat-square" />
  <img src="https://img.shields.io/badge/Base-0052FF?style=flat-square" />
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-D97757?style=flat-square" />
  <img src="https://img.shields.io/badge/Maestro_E2E-0F766E?style=flat-square" />
  <img src="https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white" />
  <img src="https://img.shields.io/badge/PostHog-1D4AFF?style=flat-square&logo=posthog&logoColor=white" />
</p>

### 🏅 Certificates

| | Certificate | Issuer |
|---|---|---|
| ✅ | [Claude Code in Action](https://verify.skilljar.com/c/8i57yi8btx7y) | Anthropic · 2026 |
| ✅ | [Introduction to Model Context Protocol](https://verify.skilljar.com/c/2aw3koz22e9t) | Anthropic · 2026 |
| ✅ | [Introduction to Subagents](https://verify.skilljar.com/c/4wcdr83jf4jd) | Anthropic · 2026 |
| ✅ | [Claude 101](https://verify.skilljar.com/c/r235mujhccvm) | Anthropic · 2026 |
| ✅ | [Advanced Flutter](https://www.udemy.com/certificate/UC-cf70fd6f-36c1-4498-95ea-05ccf4ebf4d8/) | Udemy · 2026 |
| ✅ | [Flutter Mobile: Zero to Expert](https://www.udemy.com/certificate/UC-ad4fa6be-1725-4f0f-bb2f-dac6d899a764/) | Udemy · 2024 |
| ✅ | [JavaScript Algorithms and Data Structures](https://www.freecodecamp.org/certification/fcc59fd1204-2ccd-4efa-a241-c8ef46456d6c/javascript-algorithms-and-data-structures) | freeCodeCamp · 2022 |

🏆 **1st place** Telegram ChatBot Hackathon · 🥈 **2nd place** Crypto Wallet Hackathon (Social Oplesk, 2022)

🎓 **B.S. in Computer Engineering** (Universidad Alejandro de Humboldt) · **Diploma in Web3 & Blockchain** (UCAB)

---

<div align="center">
  <sub>Most of my work lives in private Coco Wallet and Staff On repositories · <a href="./cv/Jose-Galvis-Resume-EN.pdf">Download resume (PDF)</a></sub>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:a21caf,50:5b21b6,100:0f766e&height=120&section=footer" width="100%" alt="" />
