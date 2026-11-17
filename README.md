# Enrico Sgiarovello

I build and ship software myself — currently **Fablerift**, a modern MUD you can start playing in about a
minute, plus the launcher, installers, update system and hosting kit around it. Solo author, 441 commits
and counting, released through v1.5.1.

[![Play in your browser](https://img.shields.io/badge/Play%20now-fablerift-2ea44f?style=flat-square)](https://play.fablerift.net/)
[![Latest release](https://img.shields.io/github/v/release/SleepyE5/Fablerift-releases?style=flat-square&label=Fablerift)](https://github.com/SleepyE5/Fablerift-releases/releases/latest)
[![MIT license](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](https://github.com/SleepyE5/Fablerift/blob/main/LICENSE)

## What I'm building

**Fablerift** — text-based multiplayer RPG server and client in C# on .NET 9, MIT-licensed.

- Players join from a browser, plain Telnet, or SSH against the *same* server — the browser client is the real
  world, not a demo build.
- Ships with native launcher and per-platform installers (Windows MSI, Linux AppImage, macOS arm64), SHA-256
  checked downloads, and a self-updating launcher that keeps the two previous installs for rollback.
- Embedded web admin panel for running a server, plus a public server list the client reads.
- Seven regions whose forest, coast, desert and frozen peak change with night and weather; crafting, cooking,
  player trading, party dungeons and a five-chapter story.

The source is currently a private repo; the [release and download page](https://github.com/SleepyE5/Fablerift-releases)
is public and is what the launcher reads.

## Also here

- [**photo_randomizor_and_powerpoint_maker**](https://github.com/SleepyE5/photo_randomizor_and_powerpoint_maker) —
  C# tool that randomises photos into a PowerPoint deck.
- [**Crackcraft-Github**](https://github.com/SleepyE5/Crackcraft-Github) — Minecraft modpack I maintain.
- **Echo Hunter** and **Anomalocaris** — Unity/C# projects I'm building; private until they're ready to show.
  Level-design coursework lives in private repos too.

## Open source contributions

One merged PR to upstream [Mudlet](https://www.mudlet.org): [listing Fablerift in the "All games" catalog](https://github.com/Mudlet/Mudlet/pull/12629).
I read a lot of Mudlet's Lua scripting surface while building Fablerift's client, which is where that came from.

## How I work

- C# and .NET are my daily tools; Unity and C# for the game projects, Lua for MUD client scripting.
- I ship in small versions and keep release notes, changelog and system requirements current rather than aspirational.
- Everything I claim here is something I can point at. Stats, player counts and tools I haven't actually used don't go on the page.

## Talk to me

The Fablerift community Discord is the fastest way to reach me about the game — [discord.gg/ecq88z7H9A](https://discord.gg/ecq88z7H9A).
Issues and bugs on [the release repo](https://github.com/SleepyE5/Fablerift-releases) are equally welcome.
