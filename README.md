# Awesome Internet Freedom [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, data, research, and organizations defending the open internet.

Censorship, surveillance, and internet shutdowns affect billions. This list collects the best resources for monitoring, circumventing, and documenting threats to internet freedom — from measurement platforms to encrypted communications to academic research.

**Why this list?** Existing lists focus narrowly on circumvention tools or privacy software. This list covers the full stack: measurement data, research organizations, circumvention tools, encrypted communication, AI integrations, policy resources, and developer tools for building freedom technology.

## Contents

- [Censorship Measurement & Data](#censorship-measurement--data)
- [Circumvention Tools](#circumvention-tools)
- [Encrypted Communication](#encrypted-communication)
- [VPN & Network Privacy](#vpn--network-privacy)
- [AI & Machine Learning for Freedom](#ai--machine-learning-for-freedom)
- [Agent-to-Agent Communication](#agent-to-agent-communication)
- [Browser Privacy](#browser-privacy)
- [Operating Systems & Live Environments](#operating-systems--live-environments)
- [Research Organizations](#research-organizations)
- [Policy & Advocacy](#policy--advocacy)
- [Reports & Indices](#reports--indices)
- [Developer Tools & Libraries](#developer-tools--libraries)
- [Datasets](#datasets)
- [Community & Events](#community--events)

---

## Censorship Measurement & Data

*Platforms that measure, detect, and document internet censorship in real time.*

- [Voidly Censorship Index](https://voidly.ai/censorship-index) — AI-powered censorship intelligence platform. 19.6M live measurements across 119 countries, 5,356 documented incidents, ML-based detection (99.8% F1), predictive risk forecasting, and real-time alerts. Includes MCP server, API, and HuggingFace datasets.
- [OONI (Open Observatory of Network Interference)](https://ooni.org) — Global network measurement platform. Runs probes in 200+ countries to detect blocking of websites, messaging apps, and circumvention tools. Open data.
- [CensoredPlanet](https://censoredplanet.org) — University of Michigan research platform. Automated remote measurement of DNS, HTTP, and HTTPS censorship without in-country vantage points.
- [IODA (Internet Outage Detection and Analysis)](https://ioda.inetintel.cc.gatech.edu) — Real-time monitoring of internet outages using BGP, active probing, and darknet data. Georgia Tech.
- [Netblocks](https://netblocks.org) — Real-time network intelligence. Documents internet shutdowns and service disruptions as they happen.
- [ICLab](https://iclab.org) — Internet censorship measurement lab. Uses VPN-based vantage points for longitudinal censorship studies.
- [Censored Planet Observatory](https://data.censoredplanet.org) — Public dataset of longitudinal censorship measurements across 200+ countries.
- [Cloudflare Radar](https://radar.cloudflare.com) — Internet traffic, attack, and outage insights from Cloudflare's global network.

## Circumvention Tools

*Software for bypassing internet censorship and restrictions.*

- [Tor](https://www.torproject.org) — Anonymity network routing traffic through multiple relays. The gold standard for censorship circumvention and anonymous browsing.
- [Psiphon](https://psiphon.ca) — Free circumvention tool using a combination of VPN, SSH, and HTTP proxy technology. Widely used in censored regions.
- [Lantern](https://getlantern.org) — Peer-to-peer circumvention tool that uses a trust-based network of users to route traffic.
- [Snowflake](https://snowflake.torproject.org) — Tor pluggable transport. Volunteers run browser-based proxies to help censored users connect to Tor.
- [Outline](https://getoutline.org) — Open-source VPN built on Shadowsocks. Created by Jigsaw (Google). Easy to deploy and share.
- [Shadowsocks](https://shadowsocks.org) — Lightweight encrypted proxy. Widely used in China to bypass the Great Firewall.
- [V2Ray](https://www.v2fly.org) — Platform for building proxies to bypass network restrictions. Supports multiple protocols.
- [Hysteria](https://hysteria.network) — UDP-based proxy protocol designed for unreliable and censored networks. Built on QUIC.
- [GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI) — Deep packet inspection circumvention tool for Windows. Bypasses DPI-based censorship.
- [Geneva](https://geneva.cs.umd.edu) — Genetic algorithm that automatically discovers censorship evasion strategies. University of Maryland.
- [Conjure](https://refraction.network) — Refraction networking. Uses participating ISPs to create covert communication channels.
- [Pluggable Transports](https://www.pluggabletransports.info) — Specification for transforming network traffic to avoid detection. Used by Tor, Psiphon, and others.
- [Hiddify](https://hiddify.com) — Multi-protocol proxy toolbox with auto-configuration. Popular in Iran.

## Encrypted Communication

*Messaging and communication tools with end-to-end encryption.*

- [Veil by Voidly](https://msg.voidly.ai) — E2E encrypted messenger for humans and AI agents. Double Ratchet protocol, ML-KEM-768 post-quantum encryption, deniable authentication, and voice messages. PWA — no app store required.
- [Signal](https://signal.org) — End-to-end encrypted messaging. The Signal Protocol is the gold standard for secure messaging, used by WhatsApp and others.
- [Briar](https://briarproject.org) — Peer-to-peer encrypted messaging that works over Tor, Wi-Fi, and Bluetooth. No servers required — works even when the internet is down.
- [Element (Matrix)](https://element.io) — Decentralized, encrypted communication built on the Matrix protocol. Self-hostable.
- [Session](https://getsession.org) — Decentralized messenger. No phone number required. Routes messages through an onion routing network.
- [Wire](https://wire.com) — End-to-end encrypted messaging, calls, and file sharing. Swiss-based, open source.
- [Cwtch](https://cwtch.im) — Decentralized, metadata-resistant messaging built on Tor. No servers, no phone numbers.
- [SimpleX Chat](https://simplex.chat) — No user identifiers. Uses temporary anonymous pairwise addresses for each contact.
- [Delta Chat](https://delta.chat) — Encrypted messaging over email. Works with any email provider. No servers, no tracking.

## VPN & Network Privacy

*VPN services and network-level privacy tools.*

- [Mullvad VPN](https://mullvad.net) — Privacy-focused VPN. No email, no accounts — just a generated number. Accepts cash payments.
- [ProtonVPN](https://protonvpn.com) — Swiss-based VPN with a free tier. No-logs policy, open source, Secure Core architecture.
- [IVPN](https://www.ivpn.net) — Privacy-first VPN. Open source clients, no-logs, supports WireGuard.
- [WireGuard](https://www.wireguard.com) — Modern VPN protocol. Simple, fast, and cryptographically sound. Built into the Linux kernel.
- [Tailscale](https://tailscale.com) — WireGuard-based mesh VPN. Zero-config, works behind NATs.
- [Amnezia VPN](https://amnezia.org) — Self-hosted VPN with protocol obfuscation. Designed for censored environments.

## AI & Machine Learning for Freedom

*AI tools and integrations for censorship research and internet freedom.*

- [Voidly MCP Server](https://www.npmjs.com/package/@voidly/mcp-server) — 83-tool MCP server for Claude, Cursor, and Windsurf. Query censorship data, incidents, risk forecasts, platform scores, and ISP ratings directly from your AI assistant.
- [Voidly API](https://voidly.ai/api-docs) — REST API for censorship intelligence. Incidents, predictions, platform risk scores, ISP index, service accessibility checks, election risk briefings, and real-time alerts.
- [OONI Data](https://ooni.org/data/) — Open dataset of network measurements. API access for programmatic analysis of censorship patterns.
- [CensoredPlanet Data](https://data.censoredplanet.org) — Longitudinal censorship measurement datasets for ML research.
- [Geneva](https://geneva.cs.umd.edu) — Uses genetic algorithms to automatically discover and deploy censorship evasion strategies.

## Agent-to-Agent Communication

*Protocols and tools for AI agents to communicate securely.*

- [Voidly Agent Relay (VAR)](https://voidly.ai/agents) — E2E encrypted agent-to-agent messaging. Double Ratchet, X3DH key agreement, ML-KEM-768 post-quantum, sealed sender, deniable auth, federation, and offline queue. npm SDK: `@voidly/agent-sdk`.
- [Google A2A Protocol](https://github.com/google/A2A) — Agent-to-Agent protocol specification for interoperable agent communication.
- [Model Context Protocol (MCP)](https://modelcontextprotocol.io) — Anthropic's protocol for connecting AI models to tools and data sources.

## Browser Privacy

*Web browsers and extensions focused on privacy and circumvention.*

- [Tor Browser](https://www.torproject.org/download/) — Firefox-based browser routed through the Tor network. Blocks trackers, resists fingerprinting.
- [Brave](https://brave.com) — Chromium-based browser with built-in ad blocking, tracker protection, and optional Tor integration.
- [Firefox](https://www.mozilla.org/firefox/) — Open-source browser with strong privacy controls. Enhanced Tracking Protection enabled by default.
- [Mullvad Browser](https://mullvad.net/browser) — Tor Browser without Tor. Minimizes fingerprinting for use with VPNs.
- [uBlock Origin](https://ublockorigin.com) — Efficient, wide-spectrum content blocker for browsers.
- [HTTPS Everywhere](https://www.eff.org/https-everywhere) — EFF browser extension that enforces HTTPS connections (now largely built into browsers).

## Operating Systems & Live Environments

*Privacy-focused operating systems for high-risk situations.*

- [Tails](https://tails.net) — Live operating system that routes all traffic through Tor. Boots from USB, leaves no trace.
- [Whonix](https://www.whonix.org) — Desktop OS designed for advanced security and privacy. All traffic forced through Tor via isolated VMs.
- [Qubes OS](https://www.qubes-os.org) — Security-focused OS using compartmentalization via Xen virtualization. Recommended by Edward Snowden.
- [GrapheneOS](https://grapheneos.org) — Privacy and security-focused mobile OS for Pixel phones. Hardened Android with no Google services.
- [CalyxOS](https://calyxos.org) — Privacy-focused Android with microG for minimal Google compatibility.

## Research Organizations

*Academic and nonprofit organizations studying internet censorship and digital rights.*

- [Citizen Lab](https://citizenlab.ca) — University of Toronto. Research on digital threats to civil society — spyware, censorship, surveillance.
- [Freedom House](https://freedomhouse.org) — Annual "Freedom on the Net" report ranking internet freedom in 70 countries.
- [Access Now](https://www.accessnow.org) — Digital rights nonprofit. Runs the #KeepItOn coalition tracking internet shutdowns globally.
- [Internet Freedom Foundation (IFF)](https://internetfreedom.in) — Indian digital rights organization. Advocacy, litigation, and research.
- [Open Technology Fund (OTF)](https://www.opentech.fund) — Funds internet freedom tools. Supports Tor, Signal, OONI, and many others.
- [Berkman Klein Center](https://cyber.harvard.edu) — Harvard research center on internet & society.
- [Oxford Internet Institute](https://www.oii.ox.ac.uk) — University of Oxford research on internet's societal impact.
- [ARTICLE 19](https://www.article19.org) — International organization defending freedom of expression and information.

## Policy & Advocacy

*Organizations and resources for internet freedom policy and advocacy.*

- [Electronic Frontier Foundation (EFF)](https://www.eff.org) — Leading digital rights nonprofit. Legal cases, policy advocacy, and tool development.
- [Reporters Without Borders (RSF)](https://rsf.org) — Press freedom organization. Publishes the World Press Freedom Index.
- [Committee to Protect Journalists (CPJ)](https://cpj.org) — Defends press freedom. Tracks journalist imprisonments and killings.
- [Internet Society (ISOC)](https://www.internetsociety.org) — Global organization promoting an open, globally-connected internet.
- [Digital Rights Foundation](https://digitalrightsfoundation.pk) — Pakistan-based digital rights organization.
- [Global Network Initiative (GNI)](https://globalnetworkinitiative.org) — Multi-stakeholder group promoting freedom of expression in the ICT sector.

## Reports & Indices

*Annual reports and rankings on internet freedom and censorship.*

- [Freedom on the Net](https://freedomhouse.org/report/freedom-net) — Freedom House's annual assessment of internet freedom in 70 countries.
- [Voidly Censorship Index](https://voidly.ai/censorship-index) — Live, data-driven censorship rankings. Updated continuously from 19.6M measurements.
- [World Press Freedom Index](https://rsf.org/en/index) — RSF's annual ranking of press freedom in 180 countries.
- [Access Now Shutdown Tracker](https://www.accessnow.org/campaign/keepiton/) — #KeepItOn coalition tracking internet shutdowns worldwide.
- [Google Transparency Report](https://transparencyreport.google.com/traffic/overview) — Traffic and disruption data from Google's global network.
- [OONI Reports](https://ooni.org/reports/) — Research reports on censorship events based on OONI measurement data.

## Developer Tools & Libraries

*Libraries and tools for building internet freedom technology.*

- [Voidly Agent SDK](https://www.npmjs.com/package/@voidly/agent-sdk) — E2E encrypted agent messaging SDK. Double Ratchet, X3DH, post-quantum hybrid, sealed sender, federation. `npm install @voidly/agent-sdk`
- [Voidly MCP Server](https://www.npmjs.com/package/@voidly/mcp-server) — 83 censorship intelligence tools for AI assistants. `npx @voidly/mcp-server`
- [libsignal](https://github.com/nickclaw/signal-protocol) — Signal Protocol implementation for JavaScript. Double Ratchet + X3DH.
- [tweetnacl](https://github.com/nickclaw/tweetnacl-js) — Port of NaCl cryptographic library to JavaScript. Used by many E2E encryption projects.
- [OONI Probe](https://github.com/ooni/probe-cli) — Network measurement tool. Run censorship tests from your device.
- [Stem](https://stem.torproject.org) — Python library for interacting with Tor.
- [Arti](https://gitlab.torproject.org/tpo/core/arti) — Tor client written in Rust. Modern, memory-safe reimplementation.
- [obfs4](https://gitlab.torproject.org/tpo/anti-censorship/pluggable-transports/obfs4) — Tor pluggable transport for obfuscating traffic.
- [Cloak](https://github.com/cbeuw/Cloak) — Pluggable transport disguising traffic as normal HTTPS.
- [WireGuard Tools](https://www.wireguard.com/repositories/) — Official WireGuard userspace tools and libraries.

## Datasets

*Open datasets for censorship research and analysis.*

- [Voidly Global Censorship Index](https://huggingface.co/datasets/emperor-mew/global-censorship-index) — Live JSON dataset. 119 countries, block rates, risk tiers, breakdowns. HuggingFace.
- [Voidly OONI Historical Archive](https://huggingface.co/datasets/emperor-mew/ooni-censorship-historical) — 1.6M records spanning 10 years across 120 countries. Parquet format. HuggingFace.
- [OONI Data](https://ooni.org/data/) — Complete archive of OONI network measurements. API + bulk downloads.
- [CensoredPlanet Data](https://data.censoredplanet.org) — Longitudinal censorship datasets (DNS, HTTP, HTTPS).
- [Citizen Lab Test Lists](https://github.com/citizenlab/test-lists) — URL test lists used by OONI and other measurement platforms. Community-maintained.
- [GFWatch](https://gfwatch.org) — Longitudinal dataset of China's Great Firewall DNS censorship.

## Community & Events

*Conferences, communities, and events focused on internet freedom.*

- [Internet Freedom Festival (IFF)](https://internetfreedomfestival.org) — Annual gathering of digital rights activists, developers, and researchers.
- [RightsCon](https://rightscon.org) — Global summit on human rights in the digital age.
- [Tor Dev Meetings](https://www.torproject.org/about/meetings/) — Regular meetings of the Tor developer community.
- [OONI Community](https://ooni.org/get-involved/) — Contribute to censorship measurement. Run probes, translate, or analyze data.
- [CryptoParty](https://www.cryptoparty.in) — Global grassroots movement for hands-on encryption workshops.

---

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a pull request.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
