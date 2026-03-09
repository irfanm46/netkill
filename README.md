# netkill

A browser-based lab for understanding how network attacks actually work — step by step, with real tools and commands.

No install. No backend. Open the HTML file and it works.

---

## What is this

I built this to understand offensive network security properly, not just read about it.

Most resources either go too deep (raw Wireshark captures) or too shallow ("ARP spoofing is when you fake a MAC address"). NetKill sits in the middle — it walks you through each attack phase by phase, shows you the commands attackers actually run, maps everything to MITRE ATT&CK, and simulates packet flow so you can *see* what's happening on the network.

It's not a real attack tool. Nothing executes against a real network. Think of it as an interactive reference you can use to study, prep for interviews, or understand what you're defending against.

---

## Attacks covered

| Attack | Layer | What it does |
|--------|-------|--------------|
| ARP Spoofing | L2 | Poison ARP cache, become the gateway, intercept all traffic |
| DNS Poisoning | L7 | Redirect domains to attacker-controlled servers |
| SYN Flood | L4 | Exhaust TCP connection table, take a service offline |
| VLAN Hopping | L2 | Break out of your network segment via switch exploitation |
| DHCP Starvation | L2 | Kill the real DHCP server, stand up a rogue one |
| BGP Hijacking | L3 | Reroute internet traffic at the ISP/AS level |
| Full MITM | L2–L7 | Complete traffic interception with SSL stripping |

Each one includes the full kill chain, attacker tools, detection signatures, and MITRE technique IDs.

---

## How to use it

Download `netkill.html` → open in browser → done.

Or visit the live version: [irfanm46.github.io/netkill](https://irfanm46.github.io/netkill)

1. Pick an attack from the left panel
2. Read the metrics and MITRE mapping on the right
3. Hit **Launch Attack** to run the simulation
4. Watch the detection log fire as the attack progresses
5. Review the kill chain — each phase unlocks as the simulation runs

---

## Who this is for

- Security students learning offensive concepts
- GRC / SOC analysts who want to understand what they're detecting
- Engineers who've heard terms like "ARP spoof" and want to actually get it
- Anyone prepping for security certifications or interviews

---

## Stack

Single HTML file. Vanilla JS. No frameworks, no dependencies, no npm install, no signup.

Canvas API for the network visualization. Everything runs in the browser offline.

---

## Legal

This is an educational simulator. All scenarios run in a fictional lab environment — no real networks are scanned or affected.

Performing unauthorized network attacks is illegal under the Computer Fraud and Abuse Act (CFAA), India's IT Act 2000, and equivalent laws in most countries. Only test systems you own or have explicit written permission to test.

---

## Part of the cyber-tools project

NetKill is one of a series of open-source security tools I'm building to learn by doing.

**[annexa](https://irfanm46.github.io/annexa)** — ISO 27001:2022 compliance toolkit (GRC, risk register, SoA generator, evidence wizard)

More tools coming.

---

© 2025 Irfan M — CC BY-NC-ND 4.0 — Personal and educational use only. Redistribution and derivatives not permitted.
