# Enrico Sgiarovello

Solo developer. I build and run **[Fablerift](https://fablerift.net/)**, a multiplayer text RPG you can be playing
in about a minute, along with everything around it: the desktop app, the launcher and its updates, the installers,
the hosting kit and the official server.

[Play in your browser](https://play.fablerift.net/) &nbsp;·&nbsp;
[Website](https://fablerift.net/) &nbsp;·&nbsp;
[Downloads](https://github.com/SleepyE5/Fablerift-releases/releases/latest) &nbsp;·&nbsp;
[Discord](https://discord.gg/ecq88z7H9A)

[![Latest release](https://img.shields.io/github/v/release/SleepyE5/Fablerift-releases?style=flat-square&label=release&color=2ea44f)](https://github.com/SleepyE5/Fablerift-releases/releases/latest)
[![Licence](https://img.shields.io/badge/licence-all%20rights%20reserved-blue?style=flat-square)](https://fablerift.net/LICENSE)

---

## Fablerift

The world is rooms you walk through and read, and everything you do is a word you type. Ten regions and 247
hand-written rooms, from pine forest and storm coast to desert and frozen peaks, change with night and weather. You
gather, craft, cook, trade with other players, clear dungeons as a party and follow a five-chapter story.

- **One world, any way in.** The browser, the desktop app, Telnet, SSH and Mudlet all reach the same server. The
  browser is the real game, not a demo.
- **Shipped, not just built.** 679 commits and released through v1.8.0, with installers for Windows, Linux and
  macOS and a launcher that updates itself and can roll back.
- **Run your own world.** A hosting kit for Debian or Proxmox with backups every 15 minutes, health checks,
  automatic rollback and a web admin panel.

| Part | What it runs on |
|---|---|
| Server | C# on .NET 9, JSON content packs, Telnet, SSH, WebSockets, GMCP and MSSP |
| Desktop app | Avalonia, on Windows, Linux and macOS |
| Hosting | Debian, systemd, Caddy, Cloudflare Tunnel, Tailscale Funnel |
| Source | Private. Downloads and the server list are in [Fablerift-releases](https://github.com/SleepyE5/Fablerift-releases) |

Try it from a terminal with `telnet mud.fablerift.net 4000`.

---

## Other things

- [**photo_randomizor_and_powerpoint_maker**](https://github.com/SleepyE5/photo_randomizor_and_powerpoint_maker):
  a C# tool that shuffles photos into a PowerPoint deck.
- A merged pull request to [Mudlet](https://www.mudlet.org) that adds Fablerift to its
  [games catalogue](https://github.com/Mudlet/Mudlet/pull/12629).

## Get in touch

The [Fablerift Discord](https://discord.gg/ecq88z7H9A) is the quickest way to reach me. Bug reports and questions
on [the releases repo](https://github.com/SleepyE5/Fablerift-releases) are welcome too.
