Hi, I'm Lars (alias Hackebein), located in Germany. Full time nerd, full stack and DevOps engineer at day, VR addicted at night. I love proactively working on automatization and having fun with what I create. I'm engineering and operating e-commerce platforms for more than 12 years. My free time goes atm into a [VPM Platform](https://vpmm.dev), hardware and product design for a remote controllable toy, and support for additional trackers for objects in VRChat.

## Things I work on

### VPM Mirror

License-respecting mirror of the VRChat Package Manager ecosystem. Aggregates public listings (free and paid), mirrors archives so they survive if the original host disappears, surfaces dependency graphs and filters.

- [**VPMM**](https://vpmm.dev/) — try it
- Packaging tooling: [`hackebein.vpm.packager`](https://github.com/Hackebein/hackebein.vpm.packager) (C#, Unity editor)
- The `vpm.hackebein.dev` domain now CNAMEs to VPMM.

### VRChat Wiki

I'm a contributor to the VRChat community wiki. I was invited from the beginning, and I shaped a lot of it according to my own vision. I create many of the wiki pages and contribute widely across them, not just Packages and Leaks. The full [contribution list is public](https://wiki.vrchat.com/index.php?title=Special:Contributions/Usr_40be82e7-f7d5-4548-b314-3fc7b26d22ee&target=Usr+40be82e7-f7d5-4548-b314-3fc7b26d22ee&offset=&limit=500).

<div style="display: flex; gap: 8px; align-items: center; flex-wrap: wrap;">
  <img src="https://assets.vrchat.com/badges/8a/bdgai_94e67c9a-d70a-45ab-8dec-93fe666edfdf.png" width="48" height="48" alt="VRChat Wiki Contributor badge"> <strong>VRChat Wiki Contributor</strong>
  <img src="https://assets.vrchat.com/badges/12/bdgai_c6b4e079-390e-49c3-bf2d-34b324fc1c96.png" width="48" height="48" alt="VRChat Translator badge"> <strong>VRChat Translator</strong>
</div>

#### Software I wrote for the wiki

The wiki mirror is the preservation move: a full MediaWiki → Git mirror, one commit per edit, git notes for resume, bootstrapped from a pre-state snapshot. Built because I grew uncertain how freely accessible the wiki would remain under Cloudflare bot protection.

- [`wiki.vrchat.com`](https://github.com/Hackebein/wiki.vrchat.com) (Python) — full MediaWiki → Git mirror
- [`VPMM-connector-VRCWiki`](https://github.com/Hackebein/VPMM-connector-VRCWiki) (Go) — VPMM ↔ wiki bridge
- [`vrc-api2wiki`](https://github.com/Hackebein/vrc-api2wiki) (Go) — VRChat API → wiki

#### Writing

I write about the systems I work on — wiki pages and documentations. Outside of VRChat, too.

### Bug Hunting & QA

I file bug reports, and try to break things before you do it. It just happens when I touch it. I'm currently working on a GitHub runner which is capable of running 1x VR, +3x Desktop for automated world and avatar tests.

<img src="https://assets.vrchat.com/badges/0d/bdgai_675b3973-1732-477d-940f-19f14ab0cdf6.png" width="48" height="48" alt="Community Tester (Top Contributor) badge"> **Community Tester (Top Contributor)**

The Canny scraper is an implementation of VRChat's Canny feedback board, with full Lucene search and proper previews. Canny's built-in search is a joke. This project costs about $7 per month, and VRChat is an enterprise customer spending thousands of dollars per month on the platform.

- [`feedback.vrchat.com`](https://github.com/Hackebein/feedback.vrchat.com) (TypeScript)
- Live search: [vrchat-canny.hackebein.dev](https://vrchat-canny.hackebein.dev)

### Object Tracking & performance art

Real-world objects in VRChat via SteamVR/OpenVR trackers. Sold on Steam as a Supporter Version. The performance art shares the same rig: I do aerial hoop, pole dance, and swinging bench in VR with the tracker. The repository is currently not public.

- [**Project board**](https://github.com/users/Hackebein/projects/4) — roadmap & task overview
- [**Steam**](https://store.steampowered.com/app/3140770) — auto-updating build and supporter version
- [vpm.hackebein.dev](https://vpm.hackebein.dev) — VPM listing for packages

#### Archive

- [**App (Python)**](https://github.com/Hackebein/Object-Tracking-App) — outdated desktop tracking daemon
- [**Unitypackage (C#)**](https://github.com/Hackebein/Object-Tracking-Unitypackage) — outdated avatar-side companion

### VaOBS

VRChat Video as OBS Media Source. Catches the playing video inside VRChat as its own OBS media source.

- [`VaOBS`](https://github.com/Hackebein/VaOBS) (Go)

### DoKomi

Anime/Japan convention in Düsseldorf, I've been involved since 2013 — Retro Arcade cabinets in the early years, gate / info support later. Currently core team of logistics and managing the VIP area. The convention has grown from a small (~500 visitors) local event to something much larger (~200k visitors), and it still feels like the same friendly environment.

### Game Server

I host gameservers since 2016, For hosting I prefer Docker, and maintain my own images for the games I run, some are public:

- [`docker-garrysmod`](https://github.com/Hackebein/docker-garrysmod) — Garry's Mod
- [`docker-srcds`](https://github.com/Hackebein/docker-srcds) — Source Dedicated Server (any Source engine game)
- [`docker-csgo`](https://github.com/Hackebein/docker-csgo) — CS:GO
- [`docker-ts3server`](https://github.com/Hackebein/docker-ts3server) — TeamSpeak 3

Since 2019 I run GTA Roleplay community host for FiveM, alt:V, RageMP. One community has been running on three cron jobs for years (backups, system updates, docker updates). Not glamorous. Just works.
### Tools and gearbox

Things I produced along the way: [`docker-steamcmd`](https://github.com/Hackebein/docker-steamcmd), [`wireshark-dissector-coyote3`](https://github.com/Hackebein/wireshark-dissector-coyote3), [`Hyperate-Desktop`](https://github.com/Hackebein/Hyperate-Desktop), [`VRC12Photos`](https://github.com/Hackebein/VRC12Photos), [`pro.poiyomi.com`](https://github.com/Hackebein/pro.poiyomi.com).

## Online presence

- Website: [hackebein.de](https://hackebein.de)
- Discord: [Hackebein's Research Lab](https://discord.gg/AqCwGqqQmW) — my own project server
- Bluesky: [@hackebe.in](https://bsky.app/profile/hackebe.in)
- X: [@Hackebein](https://x.com/hackebein)
- Telegram: [@Hackebein](https://t.me/Hackebein)
- Patreon: [hackebein](https://www.patreon.com/hackebein)
- PGP key: [DE68 1625 8EC5 0065 7141 3536 358C F569 8DDD 556E](https://hackebein.de/gpg.asc)
