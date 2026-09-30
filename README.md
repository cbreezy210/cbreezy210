> *"The corrupt bro dances across the NAND, thirteen bytes past the checksum, and the save never knows."* 💩

# Hi there! 👋 I'm cbreezy210
**Software Developer & Reverse Engineer**

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1500&color=FF4E8A&vCenter=true&width=440&lines=Building+native+Switch+homebrew;Reverse+engineering+save+files;Direct+NAND+injection+🔥;Training+local+AI+modules;Fixing+PCs+one+USB+at+a+time)

![GitHub Stats](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=cbreezy210&theme=radical&cachebust=30)
![Top Languages](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=cbreezy210&theme=radical)

## 📈 **1,400+ downloads served** across all projects!

## 🔧 What I Do
- Developing native save editors and homebrew for Nintendo Switch 🎮
- Reverse engineering game save formats and file structures 🕵️‍♂️
- Building local, privacy-focused AI modules (A.X.I.O.M.) 🧠
- Creating low-level system diagnostic and repair tools 💻
- Shipping zero-dependency open-source developer tools & network analysis utilities 🧰

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Nintendo Switch Homebrew](https://img.shields.io/badge/Nintendo_Switch_Homebrew-E60012?style=for-the-badge&logo=nintendoswitch&logoColor=white)
![Reverse Engineering](https://img.shields.io/badge/Reverse_Engineering-FF4500?style=for-the-badge&logo=github&logoColor=white)
![AI/LLM](https://img.shields.io/badge/AI/LLM-8A2BE2?style=for-the-badge&logo=openai&logoColor=white)

## 🚀 Currently Working On
- ⭐ **TimeStranger-NX** - Digimon Story: Time Stranger Save Editor. Direct NAND FS access successfully implemented (no bridge required!). Currently adding advanced features before public release 🎮💾🔥
- ⭐ **PKHeX-NX** - Native Pokémon SV Save Editor. v0.9.5 LIVE! 🚀 | Community Discord coming soon
- ⭐ **ACNH-Save-Editor** - Shipped v1.4.0; currently developing the v1.5.0 Room Decorations Injector
- **A.X.I.O.M. v2** - Autonomous Local AI OS | Uncensored Dungeon Master (persistent world state, combat, lore RAG), Brutal Interview Simulator, and PC Diagnostic Agent (runs offline via Ollama/ChromaDB) 🐉💻
- **Creature_AI_Prototype** - Multi-agent ecosystem simulation with persistent individual minds, emergent social dynamics, elected governance, and task delegation 🐾🏛️
- **All-in-One Tech Tools** - Bootable USB app for computer diagnosis & repair (In development, release TBD) 🛠️💻

## 🎮 My Projects
### [TimeStranger-NX](https://github.com/cbreezy210/TimeStranger-NX) 💩
![TimeStranger-NX Stars](https://img.shields.io/github/stars/cbreezy210/TimeStranger-NX?style=flat-square&logo=github&color=yellow)
![Status](https://img.shields.io/badge/Status-In_Development-yellow?style=flat-square)
![License](https://img.shields.io/github/license/cbreezy210/TimeStranger-NX?style=flat-square&color=blue&cachebust=1)

**Currently in active development:** The first native Switch save editor for Digimon Story: Time Stranger. Successfully achieved direct NAND injection (no bridge required!). Building out advanced features before public release.

🔬 **Reverse Engineering Highlights:**
- Located Yen value at offset `0x7973` (u32 little-endian) in `/savedata/0001.bin`
- Discovered the `fsFsCommit()` requirement to prevent silent NAND rollbacks
- Built custom hex-scanners to diff save dumps and locate offsets/checksums automatically

### [PKHeX-NX](https://github.com/cbreezy210/PKHeX-NX) 🔴⚪️
![PKHeX-NX Stars](https://img.shields.io/github/stars/cbreezy210/PKHeX-NX?style=flat-square&logo=github&color=yellow)
![GitHub Downloads](https://img.shields.io/github/downloads/cbreezy210/PKHeX-NX/total?style=flat-square&logo=github&color=orange)
![Latest Release](https://img.shields.io/github/v/release/cbreezy210/PKHeX-NX?include_prereleases&style=flat-square&logo=github&color=blueviolet)
![License](https://img.shields.io/github/license/cbreezy210/PKHeX-NX?style=flat-square&color=blue)

**Public Beta & actively hardening:** **A 100% native Switch save editor for Pokémon Scarlet & Violet — built with open-source C++, byte-verified backups, and dual-file commit safety.** — no PC, no save dumping, no bridges. v0.9.5 QoL sprint live; part of the 1,000+ combined downloads milestone across the native save editor portfolio.

🔬 **Reverse Engineering Highlights:**
- Cracked the Gen 9 SCBlock/SCXorShift32 save structure with SHA256 footer verification and xorpad decryption
- Ported the PKHeX `SpeciesConverter` to fix the Paldean ID divergence (Tarountula #917+ now display correctly, eliminating the "Dunsparce imposter" bug)
- Built a legality-aware generator: real abilities, manual legal move picker (pulled from real learnsets), growth-correct EXP across all 6 curves, and a 26-ball picker with correct in-game IDs
- Implemented the byte-verified backup + dual-file commit safety pipeline, alongside boot-time crypto sanity checks, SD space validation, and hard Applet-mode memory guards

📖 [GameBrew Wiki](https://www.gamebrew.org/wiki/PKHeX-NX)

💬 [GBATemp Release Thread](https://gbatemp.net/threads/homebrew-app-pkhex-nx-native-switch-pokemon-save-editor-scarlet-violet-devlog-sneak-peek.684125/)

### [ACNH-Save-Editor](https://github.com/cbreezy210/ACNH-Save-Editor) 🍃
![ACNH Stars](https://img.shields.io/github/stars/cbreezy210/ACNH-Save-Editor?style=flat-square&logo=github&color=yellow)
![GitHub Downloads](https://img.shields.io/github/downloads/cbreezy210/ACNH-Save-Editor/total?style=flat-square&logo=github&color=orange)
![GameBanana](https://img.shields.io/badge/GameBanana-284%2B%20Downloads-F5A623?style=flat-square&logo=gamebanana&logoColor=white)
![Latest Release](https://img.shields.io/github/v/release/cbreezy210/ACNH-Save-Editor?style=flat-square&logo=github&color=blueviolet)
![License](https://img.shields.io/github/license/cbreezy210/ACNH-Save-Editor?style=flat-square&color=blue)

**Shipped & stable:** The first 100% native Switch save editor for Animal Crossing: New Horizons — no PC, no save dumping, no bridges. v1.4.0 live with 1,000+ combined downloads across GitHub + GameBanana; v1.5.0 Room Decorations Injector in active development.

🔬 **Reverse Engineering Highlights:**
- Cracked the AES-encrypted economy integers (Wallet, Bank, Nook Miles, Loan) split across `personal.dat` (per-resident) and `main.dat` (per-island)
- Implemented automatic Murmur3 hash healing so edited saves pass the game's integrity checks on first boot
- Mapped the pocket item table: 8-byte slot records at offset `0x2A00` under `/Villager0/`, powered by a 13,000+ item-name database with native keyboard search
- Built the byte-verified backup + dual-file commit safety pipeline (auto SD backup before every NAND write, one-tap ZL rollback) — 1,000+ installs, zero lost saves

📖 [GameBrew Wiki](https://www.gamebrew.org/wiki/ACNH_Save_Editor_Switch)

💬 [GBATemp Release Thread](https://gbatemp.net/threads/release-acnh-save-editor-a-new-save-editor-for-animal-crossing-new-horizons.683771/)

## 💬 From the Trenches

> *"Your Phase 0 feedback helped us catch exactly the kind of portability issues we wanted to eliminate."*  
> — **akino-nanto**, flamoris-ai-agent maintainer *(on PR #20, which merged the refactor my Phase 0 testing triggered)*

> *"direct NAND save interaction is fucking sick"*  
> — **u/Duffmcmcmcwhalen**, r/SwitchHacks *(on the TimeStranger-NX devlog)*

> *"YO THIS IS INSANE. HUGE PROPS"*  
> — **u/riskyjones**, r/SwitchHacks *(on the TimeStranger-NX devlog)*

> *"I told my niece I corrupted her island... she dubbed you 'Corrupt Bro'. Restoring the Zelda save sounds complicated so I think I'm going to stop but I'm happy the switch is working again. Again, you're an awesome person for taking the time to help me troubleshoot."*  
> — **igomhn3**, ACNH-Save-Editor User *(after a successful NAND rescue! 😎) (shared with permission)*

> *"I need to write up a small 'how to' document for my non-tech-savvy wife... Would you like me to post it here so you can use whatever part of it that you want for helping others?"*  
> — **micaturtle**, Tech Support Pro & Community Collaborator *(After catching a folder naming bug in v1.4.0, they helped fix the release zip and volunteered to write an accessibility guide)*

> *"Can someone please bring native PKHeX on switch with support for all gens... You got all my support my friend!"*  
> — **z-shark**, Homebrew Community Member *(After seeing my ACNH editor, they confirmed native PKHeX-NX was exactly what the community needed)*

> *"OMG Cbreezy! You are the GOAT! I haven't even opened it yet, and this looks AWESOME. :D - the pocket item injection will be awesome! Thank you SO much :D"*  
> — **micaturtle**, ACNH Modding Community *(On launch day of v1.0; later helped fix broken links and volunteered to write accessibility guides)*

## 🤖 AI Projects
### A.X.I.O.M. v2 — Autonomous Local AI OS
<p align="center">
<img src="assets/axiom_resume_interview.png" width="45%" alt="Resume Parser & Interview Simulator" />
<img src="assets/axiom_job_kanban.png" width="45%" alt="Job Hunt Kanban Board" />
</p>
<p align="center">
<em>Left: Resume Parser + Brutal Interview Simulator | Right: Job Hunt Kanban Tracker</em>
</p>

<p align="center">
<img src="assets/axiom_dnd_mode.png?v=2" width="60%" alt="A.X.I.O.M. D&D Dungeon Master Mode" />
</p>
<p align="center">
<em>D&D Mode with Grit Level slider, Character Creation & Campaign Management</em>
</p>

<p align="center">
<img src="assets/axiom_rulebook_rag.png" width="60%" alt="A.X.I.O.M. Rulebook RAG System" />
</p>
<p align="center">
<em>A.X.I.O.M. ingests the official D&D 5e SRD via ChromaDB for accurate rule-based narration</em>
</p>

**Features:**
- 🐉 **Uncensored Dungeon Master** — Persistent world state, combat tracking, lore RAG, session chronicles
- 💼 **Brutal Interview Simulator** — Realistic hiring manager persona with scored feedback
- 📄 **Resume Parser & Job Hunter** — PDF parsing, automated job search, cover letter generation
- 🛠️ **PC Diagnostic Agent** — Executes local PowerShell tools safely via permission gate
- 🧠 **Fully Offline** — Runs on Ollama + ChromaDB, zero data leaves your machine

### Creature_AI_Prototype — Multi-Agent Ecosystem Simulation
<p align="center">
<img src="assets/creature_ai_habitat.png" width="70%" alt="Creature AI Habitat Dashboard" />
</p>
<p align="center">
<em>Emergent colony governance with elected mayors, task delegation, and persistent creature relationships</em>
</p>

**Features:**
- 🧠 **Persistent Individual Minds** — Each creature has unique memory, personality, and relationship maps
- 🏛️ **Elected Governance** — Dynamic mayor elections with leadership scores and task assignment
- 🤝 **Social Dynamics** — Creatures refuse tasks based on friendship levels, form alliances, and negotiate
- ⏱️ **Time & Weather System** — Day/night cycles, weather effects, and resource management

## 🤝 Recent Open-Source Contributions
- **[r/SwitchPirates 23.0.0 Recovery Guide](https://www.reddit.com/r/SwitchPirates/s/9IyhbWkFE3) — 13k+ views, 50+ shares, support thread with 23+ comments; maintained with a public corrections log and maintainer-verified fixes (bth, hexkyz).
- **[GitProfileLens](https://github.com/quangshuynh/gitprofilelens) (Accessibility & Testing):** Implemented keyboard-accessible copy feedback with `aria-live` announcements and robust clipboard error handling. Rewrote unit tests to exercise real production handlers, ensuring deterministic success/failure paths.
- **[Repo-Radar](https://github.com/quangshuynh/repo-radar) (Algorithmic Disambiguation):** Fixed a semantic collision in recommendation ranking where the "homebrew" keyword falsely matched macOS `brew` taps instead of Nintendo Switch homebrew projects, preserving relevance for console dev profiles.
- **[flamoris-ai-agent](https://github.com/flamoris-jp/flamoris-ai-agent) (Phase 0 Validation & Architecture Impact):** Independently executed the full local acceptance checklist for a runtime-agnostic local AI agent on Windows. Identified critical friction points (UTF-8 encoding traps, API provider mismatches) which directly influenced the maintainer's architectural refactor ([PR #20](https://github.com/flamoris-jp/flamoris-ai-agent/pull/20)) for a neutral, environment-driven setup flow.
- **[OpenNOW-Switch](https://github.com/OpenCloudGaming/OpenNOW-Switch) (Real Hardware QA):** Conducted deep hardware acceptance testing on modded Switch. Isolated a DTLS stream negotiation hang, validated the upstream fix (PR #37), and caught a critical global input regression (touch + Joy-Con HID) that CI missed, preventing a broken stable release.
- **[Dusklight](https://github.com/HayatoG/dusklight) (Release Engineering):** Diagnosed a version mismatch between the `.nro` NACP metadata and the in-game menu (`git describe --dirty`). Proposed three distinct CMake/release pipeline solutions, drawing from direct experience shipping `PKHeX-NX`.

## 💼 Available for Freelance & Contract Work

I leverage my deep expertise in **reverse engineering**, **systems programming**, and **local AI architecture** to help companies and developers solve complex technical challenges. I prioritize **safety**, **transparency**, and **byte-verified integrity** in every project.

### ✍️ Technical Writing & Documentation
*I translate complex low-level concepts into clear, actionable guides for developers and end-users.*
- **Specialties:** Reverse engineering tutorials, API documentation, save-format breakdowns, and security best practices.
- **Recent Work:** Authored the [r/SwitchPirates 23.0.0 Recovery Guide](https://www.reddit.com/r/SwitchPirates/s/9IyhbWkFE3) (13k+ views, #6 post of all time on r/SwitchPirates) and contributed accessibility docs for [GitProfileLens](https://github.com/quangshuynh/gitprofilelens).
- **Ideal For:** Developer blogs, SDK documentation, and community-facing technical guides.

### 🐛 Bug Bounty Hunting & Security Auditing
*I find the edge cases that CI pipelines miss, focusing on memory safety, crypto implementations, and file system integrity.*
- **Specialties:** Native application hardening, hash verification logic, NAND/file-system commit mechanisms (`fsFsCommit()`), and local AI model security.
- **Track Record:** Identified critical input regressions in [OpenNOW-Switch](https://github.com/OpenCloudGaming/OpenNOW-Switch) and architectural friction points in [flamoris-ai-agent](https://github.com/flamoris-jp/flamoris-ai-agent).
- **Ideal For:** Pre-release security audits, homebrew tool hardening, and local-first AI application testing.

### 🛠️ Specialized IT Support & Systems Engineering
*I build zero-dependency tools and diagnostic agents that respect user privacy and system integrity.*
- **Specialties:** Python CLI automation, network diagnostics, local LLM integration (Ollama/ChromaDB), and Windows/Linux system repair.
- **Tools Built:** [gh-network-scanner](https://github.com/cbreezy210/gh-network-scanner) (zero-dep network mapping) and A.X.I.O.M. PC Diagnostic Agent.
- **Ideal For:** Automating internal dev-ops tasks, building custom diagnostic tools, or setting up secure, offline AI workflows.

---
**📩 Contact:** For inquiries, please reach out via [GitHub Issues](https://github.com/cbreezy210/cbreezy210/issues) or connect with me on [Bluesky](https://bsky.app/profile/cbreezy210.bsky.social).

## 🧰 Open-Source Dev Tools
### [gh-network-scanner](https://github.com/cbreezy210/gh-network-scanner) 🕸️
![Scanner Stars](https://img.shields.io/github/stars/cbreezy210/gh-network-scanner?style=flat-square&logo=github&color=yellow)
![License](https://img.shields.io/github/license/cbreezy210/gh-network-scanner?style=flat-square&color=blue)
![Python](https://img.shields.io/badge/Python-stdlib-3776AB?style=flat-square&logo=python&logoColor=white)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-239120?style=flat-square)

**Shipped & live:** A zero-dependency, safety-first CLI that maps your second-degree GitHub network to surface high-signal developers. Pure Python stdlib — no pip, no frameworks. Applies a strict Quality Gate to filter bots and mass-followers, then enriches survivors with repo-language data. This is the exact tool that recently surfaced and connected me with Switch homebrew legends (ClusterM, fincs, WinterMute) and local-AI architects, proving the zero-dependency, safety-first architecture in the wild.

## 🔗 Find Me
- [GBATemp](https://gbatemp.net/members/cbreezy210.619217/)
- [GameBanana](https://gamebanana.com/members/5799686)
- [Reddit](https://www.reddit.com/u/cbreezy210/s/ICYg6ZXcbK)
- [Bluesky](https://bsky.app/profile/cbreezy210.bsky.social)

## 📊 GitHub Activity
![Commit Activity](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=cbreezy210&theme=radical&cachebust=30)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=cbreezy210&theme=radical&hide_border=true)

### 🐍 Contribution Snake
![Snake animation](https://raw.githubusercontent.com/cbreezy210/cbreezy210/output/github-snake-dark.svg)

---
### 💖 Support This Work
I build native Switch homebrew, zero-dependency save editors, and local-first AI systems. All my tools are open-source, safety-first, and byte-verified. 

If you've benefited from my work—whether it's rescuing a corrupted island, editing Pokémon saves on your Switch, or exploring local AI architecture—your support helps me keep building tools you can trust.

<a href="https://www.buymeacoffee.com/cbreezy210" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

---
⭐ **Found this useful?** Star my repos and follow my work!

*Built with ❤️ and lots of coffee* ☕

<div align="center">
<img src="https://komarev.com/ghpvc/?username=cbreezy210&style=flat&color=blueviolet&label=Profile+Views" alt="Profile Views" />
</div>
