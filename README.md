## Iain Hoggan

IT & Network Technician based in the Wirral, UK. I work across Windows,
Microsoft 365 and network infrastructure by day, and in my own time build
simulation software in Python and run local AI on hardware rescued from
the scrap pile.

Whatever I'm working on, I hold to the same standard: claims are enforced
by something runnable, and verification is broken on purpose before it's
trusted — a check that has only ever passed proves nothing.

### Professional

**[powershell-reference](https://github.com/ihoggan/powershell-reference)** —
reference sheets for Active Directory, Entra ID, network discovery and
endpoint support, written for PowerShell 7 with the 5.1 differences called
out. Every snippet is put through the real PowerShell parser in CI, scanned
for internal identifiers before it can be committed, and the language
claims are executed rather than asserted.

### Local AI on old hardware

**[localcast](https://github.com/ihoggan/localcast)** — persistent
characters for local models running on Ollama. Each character keeps a diary
of facts and a conversation history that survive restarts; new diary
entries are extracted at the end of a session and only kept once I've
reviewed them. Changes to the extractor are measured against a scripted,
blind-graded evaluation rather than judged by eye. No cloud, no
subscription.

**[nix6-tools](https://github.com/ihoggan/nix6-tools)** — the setup guide
and Bash bootstrap scripts behind every Python project I start on a
reclaimed desktop running Ubuntu: one-time machine setup, then a single
command to scaffold a project, its in-folder venv and its GitHub repo.
Written for a beginner and tested by following it as one.

### Personal projects

**[HUSTLER](https://github.com/ihoggan/hustler)** — a UK blackball pool
physics sandbox built on pygame and pymunk. Real-world table geometry to
WEPF spec, utility-based AI opponents, and a tracked shot log that feeds
back into calibration, so changes to the physics or the AI can be measured
rather than guessed at. Continuous integration on every push.

**[playbook](https://github.com/ihoggan/playbook)** — the working practices
I distilled out of HUSTLER: how I scope an increment, verify it, and keep a
long-running project honest with itself. Reused on everything I start now.

### Toolkit

**Windows & M365** — PowerShell 7 · Active Directory · Entra ID &
Microsoft Graph · Exchange Online · endpoint support

**Linux & command line** — Ubuntu, Debian, Raspberry Pi OS · Bash
scripting and provisioning · Apache, FTP, SSH and remote administration ·
vim, nano, dotfile configuration

**Networking** — infrastructure support · wireless configuration and
monitor-mode capture · nmap · DNS, DHCP, IPv6 · access point and routed
setups

**Python** — pandas, matplotlib & seaborn for reporting and cost analysis ·
scikit-learn (classification, clustering, model evaluation) · neural
network fundamentals from scratch · requests & BeautifulSoup · tkinter ·
unittest · pygame & pymunk

**Local AI** — Ollama · running and prompting local models · persistent
memory and evaluation harnesses

**Practice** — Git & GitHub Actions · CI and automated testing

### Elsewhere

[Digital portfolio](https://ihoggan.github.io/) ·
[Saved from the scrap pile](https://ihoggan.github.io/reclaim.html) — how an
old desktop became a Linux machine running local AI characters
