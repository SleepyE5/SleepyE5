# Hi, I'm Enrico

I'm a solo developer. Most of my time goes into **[Fablerift](https://fablerift.net/)**, a modern
MUD you can start playing in about a minute, along with everything around it: the desktop app, the launcher and
its update system, the installers, the hosting kit and the official server.

[![Play now](https://img.shields.io/badge/play%20now-play.fablerift.net-2ea44f?style=flat-square)](https://play.fablerift.net/)
[![Latest release](https://img.shields.io/github/v/release/SleepyE5/Fablerift-releases?style=flat-square&label=release)](https://github.com/SleepyE5/Fablerift-releases/releases/latest)
[![Discord](https://img.shields.io/badge/discord-join-5865F2?style=flat-square)](https://discord.gg/ecq88z7H9A)
[![Website](https://img.shields.io/badge/site-fablerift.net-555?style=flat-square)](https://fablerift.net/)
[![Licence](https://img.shields.io/badge/licence-all%20rights%20reserved-blue?style=flat-square)](https://fablerift.net/LICENSE)

## Fablerift

A text RPG you play with other people. The world is rooms you walk through and read, and everything you do is a
word you type. Ten regions and 247 hand-written rooms, from pine forest and storm coast to desert and frozen
peaks, change with night and weather. You gather, craft, cook, trade with other players, clear dungeons as a party
and follow a five-chapter story.

**One world, any way in.** The browser client, the desktop app, plain Telnet, SSH and Mudlet all connect to the
same server. The browser is the real game, not a demo build, and Mudlet gets its map and status over GMCP.

**Shipped like a real product.** 679 commits in and released through v1.8.0. Installers for Windows, Linux and macOS,
checksummed downloads, and a launcher that updates itself and keeps the last two installs for rollback.

**Run your own world.** The hosting kit sets up a server on Debian or Proxmox with backups every 15 minutes,
health checks and automatic rollback. It also has a web admin panel with two-step sign-in, and content packs
let people add their own areas.

| | |
|---|---|
| Server | C# on .NET 9, JSON content, Telnet, SSH (FxSsh), WebSockets, GMCP and MSSP |
| Desktop app | Avalonia, on Windows, Linux and macOS |
| Hosting | Debian, systemd, Caddy, Cloudflare Tunnel, Tailscale Funnel |
| Source | Private. Downloads and the server list live in [Fablerift-releases](https://github.com/SleepyE5/Fablerift-releases) |

## Other things

- [**photo_randomizor_and_powerpoint_maker**](https://github.com/SleepyE5/photo_randomizor_and_powerpoint_maker):
  a C# tool that shuffles photos into a PowerPoint deck.
- One merged pull request to [Mudlet](https://www.mudlet.org), adding Fablerift to its
  [games catalogue](https://github.com/Mudlet/Mudlet/pull/12629).

## Get in touch

The [Fablerift Discord](https://discord.gg/ecq88z7H9A) is the quickest way to reach me. Bug reports and questions
on [the releases repo](https://github.com/SleepyE5/Fablerift-releases/issues) are welcome too.
