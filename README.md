<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1500&color=FF4E8A&vCenter=true&width=600&lines=The+corrupt+bro+dances+across+the+NAND;thirteen+bytes+past+the+checksum;and+the+save+never+knows.+%F0%9F%92%A9" alt="Corrupt Bro Banner" />
</p>

# Hi, I'm cbreezy210 (Corrupt Bro) 👋
**Software Developer | Reverse Engineer | Local-First AI Architect**

I build native Nintendo Switch homebrew, zero-dependency save editors, and offline AI systems. My doctrine is simple: byte-verified or it doesn't ship. I maintain a public corrections log, prioritize safety-first engineering, and let the code speak for itself.

<details>
<summary><strong>📑 Quick Navigation (Click to Expand)</strong></summary>
<br>
• <a href="#-impact--metrics">Impact & Metrics</a><br>
• <a href="#️-tech-stack">Tech Stack</a><br>
• <a href="#-featured-projects">Featured Projects</a><br>
• <a href="#-open-source-contributions">Open Source Contributions</a><br>
• <a href="#-ai--local-systems">AI & Local Systems</a><br>
• <a href="#-from-the-trenches">From the Trenches</a><br>
• <a href="#-lets-work-together">Let's Work Together</a>
</details>

---

##  Impact & Metrics
- **1,800+ downloads** served across all open-source projects.
- **#1 Post of All Time** on r/SwitchPirates: Atmosphere 1.12.1 announcement (17.8k views, 85 upvotes, 99% upvote ratio, 63 comments, 10 shares).
- **#2 Post of All Time** on r/SwitchPirates: FW 23.0.0 Recovery Guide (26.9k views, 82 shares, 46 comments, 91% upvote ratio) - maintained with a public corrections log and maintainer-verified fixes (bth, hexkyz).
- **Zero lost saves** across 1,000+ installs of ACNH-Save-Editor, thanks to a byte-verified backup + dual-file commit safety pipeline.
- **Global Reach:** Top viewers from United States (42.4%), Canada (8.6%), Germany (11.5%), Brazil (4.3%), and UK (5.5%).

---

## 🛠️ Tech Stack
**Languages:**

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Systems & Low-Level:** ![Horizon OS & Homebrew](https://img.shields.io/badge/Horizon_OS_&_Homebrew-E60012?style=for-the-badge&logo=nintendoswitch&logoColor=white) ![Reverse Engineering](https://img.shields.io/badge/Reverse_Engineering-FF4500?style=for-the-badge&logo=github&logoColor=white) ![Cryptography](https://img.shields.io/badge/Cryptography_(AES/SHA256)-2D3748?style=for-the-badge&logo=linux&logoColor=white)

**AI & Tools:** ![Local AI](https://img.shields.io/badge/Local_AI_(Ollama/ChromaDB)-8A2BE2?style=for-the-badge&logo=openai&logoColor=white) ![Zero Dependencies](https://img.shields.io/badge/Zero_Dependencies-239120?style=for-the-badge)

---

## 🚀 Featured Projects

### 🟡 [PKHeX-NX](https://github.com/cbreezy210/PKHeX-NX) 🔴⚪️ *(Active Beta)*
![PKHeX-NX Stars](https://img.shields.io/github/stars/cbreezy210/PKHeX-NX?style=flat-square&logo=github&color=yellow) ![Downloads](https://img.shields.io/github/downloads/cbreezy210/PKHeX-NX/total?style=flat-square&logo=github&color=orange)

**A 100% native Switch save editor for Pokémon Scarlet & Violet.** No PC, no save dumping, no bridges. v0.9.5 QoL sprint live.
- **RE Highlights:** Cracked Gen 9 SCBlock/SCXorShift32 save structure with SHA256 footer verification. Ported PKHeX `SpeciesConverter` to fix Paldean ID divergence. Built a legality-aware generator with real learnsets and growth-correct EXP curves.
- 📖 [GameBrew Wiki](https://www.gamebrew.org/wiki/PKHeX-NX) | 💬 [GBATemp Thread](https://gbatemp.net/threads/homebrew-app-pkhex-nx-native-switch-pokemon-save-editor-scarlet-violet-devlog-sneak-peek.684125/)

### 🟢 [ACNH-Save-Editor](https://github.com/cbreezy210/ACNH-Save-Editor) 🍃 *(Stable)*
![ACNH Stars](https://img.shields.io/github/stars/cbreezy210/ACNH-Save-Editor?style=flat-square&logo=github&color=yellow) 
![GitHub Downloads](https://img.shields.io/github/downloads/cbreezy210/ACNH-Save-Editor/total?style=flat-square&logo=github&color=orange) 
![GameBanana](https://img.shields.io/badge/GameBanana-336%2B%20Downloads-F5A623?style=flat-square&logo=gamebanana&logoColor=white)

**The first 100% native Switch save editor for Animal Crossing: New Horizons.** v1.4.0 live (1,536+ downloads). v1.5.0 Room Decorations Injector in dev.
- **RE Highlights:** Cracked AES-encrypted economy integers split across `personal.dat` and `main.dat`. Implemented automatic Murmur3 hash healing. Mapped the pocket item table (8-byte slot records at `0x2A00`) powered by a 13,000+ item database.

### 🟡 [TimeStranger-NX](https://github.com/cbreezy210/TimeStranger-NX) 💩 *(Active Dev)*
![TimeStranger-NX Stars](https://img.shields.io/github/stars/cbreezy210/TimeStranger-NX?style=flat-square&logo=github&color=yellow)

**The first native Switch save editor for Digimon Story: Time Stranger.** 
- **RE Highlights:** Achieved direct NAND FS access (no bridge required). Located Yen value at offset `0x7973` (u32 LE). Discovered the `fsFsCommit()` requirement to prevent silent NAND rollbacks.

### 🟡 [Fallout: Evolution](https://github.com/rh-hideout/pokeemerald-expansion) *(Collaboration)*
Fallout-themed Pokémon ROM hack led by **abelardthebard**. Contributing creature design, BST/stat balancing, lore-to-mechanics ability mapping, and type-chart optimization. Currently locking in the early-game batch (Dogmeat starter branches, Mutant Hound lines).

---

## 🤝 Open-Source Contributions
- **[r/SwitchPirates 23.0.0 Recovery Guide](https://www.reddit.com/r/SwitchPirates/comments/1wtuu8e/fw_2300_atmosphere_1120_fixed_the_yellow_screen/)**: Authored the definitive troubleshooting guide. Maintained with a public corrections log and maintainer-verified fixes (bth, hexkyz).
- **[OpenNOW-Switch](https://github.com/OpenCloudGaming/OpenNOW-Switch)**: Conducted deep hardware QA. Isolated a DTLS stream negotiation hang, caught a critical global input regression that CI missed, and held the QA block on the native-Switch implementation to document a lifecycle crash before merge.
- **[flamoris-ai-agent](https://github.com/flamoris-jp/flamoris-ai-agent)**: Executed full local acceptance checklist. Identified critical friction points (UTF-8 encoding traps, API mismatches) which directly influenced the maintainer's architectural refactor ([PR #20](https://github.com/flamoris-jp/flamoris-ai-agent/pull/20)).
- **[GitProfileLens](https://github.com/quangshuynh/gitprofilelens)**: Implemented keyboard-accessible copy feedback with `aria-live` announcements and rewrote unit tests to exercise real production handlers.
- **[Dusklight](https://github.com/HayatoG/dusklight)**: Diagnosed a version mismatch between `.nro` NACP metadata and the in-game menu. Proposed three distinct CMake/release pipeline solutions.

---

## 🤖 AI & Local Systems

### A.X.I.O.M. v2 — Autonomous Local AI OS
<p align="center">
  <img src="assets/axiom_resume_interview.png" width="45%" alt="Resume Parser & Interview Simulator" />
  <img src="assets/axiom_job_kanban.png" width="45%" alt="Job Hunt Kanban Board" />
</p>
<p align="center"><em>Left: Resume Parser + Brutal Interview Simulator | Right: Job Hunt Kanban Tracker</em></p>
- 🐉 **Uncensored Dungeon Master:** Persistent world state, combat tracking, lore RAG, session chronicles.
- 💼 **Brutal Interview Simulator:** Realistic hiring manager persona with scored feedback.
- 🛠️ **PC Diagnostic Agent:** Executes local PowerShell tools safely via permission gate.
- 🧠 **Fully Offline:** Runs on Ollama + ChromaDB. Zero data leaves the machine.

### Creature_AI_Prototype — Multi-Agent Ecosystem
<p align="center">
  <img src="assets/creature_ai_habitat.png" width="70%" alt="Creature AI Habitat Dashboard" />
</p>
<p align="center"><em>Emergent colony governance with elected mayors, task delegation, and persistent creature relationships</em></p>
- 🧠 **Persistent Individual Minds:** Unique memory, personality, and relationship maps per agent.
- 🏛️ **Elected Governance:** Dynamic mayor elections with leadership scores and task assignment.

## 🧰 Developer Tools

### 🟢 [gh-network-scanner](https://github.com/cbreezy210/gh-network-scanner) 🕸️ *(Stable)*
![Stars](https://img.shields.io/github/stars/cbreezy210/gh-network-scanner?style=flat-square&logo=github&color=yellow) ![Python](https://img.shields.io/badge/Python-stdlib-3776AB?style=flat-square&logo=python&logoColor=white) ![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-239120?style=flat-square)
**A zero-dependency, safety-first CLI that maps your second-degree GitHub network to surface high-signal developers.** Pure Python stdlib — no pip, no frameworks.
- **Smart Quality Gate:** Automatically filters out bots, mass-followers (>800 following), and empty accounts (<3 repos) to find true domain experts.
- **Real-World Proof:** Used this exact tool to discover and connect with Switch homebrew legends (ClusterM, fincs, WinterMute) and local-AI architects.

---

## 💬 From the Trenches
See what the community and collaborators are saying about my work in [TESTIMONIALS.md](TESTIMONIALS.md).

> *"Your Phase 0 feedback helped us catch exactly the kind of portability issues we wanted to eliminate."*  
> — **akino-nanto**, flamoris-ai-agent maintainer *(on PR #20)*

> *"I told my niece I corrupted her island... she dubbed you 'Corrupt Bro'. Restoring the Zelda save sounds complicated so I think I'm going to stop but I'm happy the switch is working again. Again, you're an awesome person for taking the time to help me troubleshoot."*  
> — **igomhn3**, ACNH-Save-Editor User *(after a successful NAND rescue)*

> *"Thanks for the heads up on the dvr patches. I don't have any reason to update my emummc right now but when I do update it and my games crash, I'll know why"*  
> — **SwellEquis**, r/SwitchPirates *(preventative harm reduction working in the wild)*
---

## 💼 Let's Work Together
I leverage deep expertise in reverse engineering, systems programming, and local AI architecture to solve complex technical challenges. I prioritize safety, transparency, and byte-verified integrity.

- **✍️ Technical Writing:** Translating low-level concepts into actionable guides (e.g., the 26.9k+ view r/SwitchPirates recovery guide).
- **🐛 Security Auditing & QA:** Finding edge cases CI misses. Focused on memory safety, crypto implementations, and Horizon OS crash-screen decoding.
- **🛠️ Systems Engineering:** Building zero-dependency diagnostic agents for secure, offline workflows.

📩 **Contact:** [christopherbrownii1993@gmail.com](mailto:christopherbrownii1993@gmail.com)  
🌐 **Connect:** [Bluesky](https://bsky.app/profile/cbreezy210.bsky.social) | [GBATemp](https://gbatemp.net/members/cbreezy210.619217/) | [GameBanana](https://gamebanana.com/members/5799686)

---

### 💖 Support This Work
I build native Switch homebrew, zero-dependency save editors, and local-first AI systems. All my tools are open-source, safety-first, and byte-verified. If you've benefited from my work, your support helps me keep building tools you can trust.

<p align="center">
  <a href="https://www.buymeacoffee.com/cbreezy210" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important; width: 217px !important;" />
  </a>
</p>

---
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=cbreezy210&style=flat&color=blueviolet&label=Profile+Views" alt="Profile Views" />
  <br><br>
  <img src="https://raw.githubusercontent.com/cbreezy210/cbreezy210/output/github-snake-dark.svg" alt="Contribution Snake" />
</p>
