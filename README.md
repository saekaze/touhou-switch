# Touhou Project on Nintendo Switch

![Platform](https://img.shields.io/badge/Platform-Nintendo%20Switch-e60012?style=for-the-badge&logo=nintendoswitch&logoColor=white)
![Ports](https://img.shields.io/badge/Ports-6%20games%20%2B%201%20fangame-8a2be2?style=for-the-badge)

Native homebrew ports of the Touhou Project games for the **Nintendo Switch** (Horizon OS / Atmosphère) — no Linux, Box64 or Wine. Every port runs straight from hbmenu, uses the same controls and can live in one shared folder on the SD card.

> ⚠️ These repositories contain **only the homebrew engine code**. No game files are distributed — you need your own legally owned copy of each game.

---

## ⭐ Official Touhou games — ZUN / Team Shanghai Alice

| | Game | Port version | Download | Source |
| :---: | :--- | :---: | :---: | :---: |
| <img width="96" alt="Touhou 6" src="https://github.com/user-attachments/assets/f7d4ce1a-acb3-49a5-b952-2fae2df142b3" /> | **Touhou 6: the Embodiment of Scarlet Devil**<br>東方紅魔郷 (2002) · needs v1.02h | 1.02h-r2 | [touhou6.nro](https://github.com/saekaze/th06-switch/releases/latest) | [th06-switch](https://github.com/saekaze/th06-switch) |
| <img width="96" alt="Touhou 7" src="https://github.com/user-attachments/assets/d1fed52e-2bad-4d12-acb7-7104aa4129bc" /> | **Touhou 7: Perfect Cherry Blossom**<br>東方妖々夢 (2003) · needs v1.00b | 1.00b-r5 | [touhou7.nro](https://github.com/saekaze/th07-switch/releases/latest) | [th07-switch](https://github.com/saekaze/th07-switch) |
| <img width="96" alt="Touhou 8" src="https://github.com/user-attachments/assets/57d8c201-1bc7-4ac9-af62-d41f41f9c7e0" /> | **Touhou 8: Imperishable Night**<br>東方永夜抄 (2004) · needs v1.00d | 1.00d-r4 | [touhou8.nro](https://github.com/saekaze/th08-switch/releases/latest) | [th08-switch](https://github.com/saekaze/th08-switch) |
| <img width="96" alt="Touhou 9" src="https://raw.githubusercontent.com/saekaze/th09-switch/main/platform/switch/icon.jpg" /> | **Touhou 9: Phantasmagoria of Flower View**<br>東方花映塚 (2005) · needs v1.50a | 1.50a-r2 | [touhou9.nro](https://github.com/saekaze/th09-switch/releases/latest) | [th09-switch](https://github.com/saekaze/th09-switch) |
| <img width="96" alt="Touhou 10" src="https://github.com/user-attachments/assets/d9c33e0a-3a37-4b76-a2a6-7d73729cd6b7" /> | **Touhou 10: Mountain of Faith**<br>東方風神録 (2007) · needs v1.00a | 1.00a-r5 | [touhou10.nro](https://github.com/saekaze/th10-switch/releases/latest) | [th10-switch](https://github.com/saekaze/th10-switch) |
| <img width="96" alt="Touhou 11" src="https://raw.githubusercontent.com/saekaze/th11-switch/main/platform/switch/icon.jpg" /> | **Touhou 11: Subterranean Animism**<br>東方地霊殿 (2008) · needs v1.00a | 1.00a-r3 | [touhou11.nro](https://github.com/saekaze/th11-switch/releases/latest) | [th11-switch](https://github.com/saekaze/th11-switch) |

## 🌙 Fan games

| | Game | Download | Source |
| :---: | :--- | :---: | :---: |
| <img width="96" alt="Wonderful Waking World" src="https://raw.githubusercontent.com/saekaze/thWWW-switch/main/assets/icon.jpg" /> | **東方眠世界 ~ Wonderful Waking World** by Oligarchomp · needs the free 1.0.1 release from [itch.io](https://oligarchomp.itch.io/wonderful-waking-world)<br>⚠️ *Playable now — an update to improve performance is coming later.* | [thwww.nro](https://github.com/saekaze/thWWW-switch/releases) | [thWWW-switch](https://github.com/saekaze/thWWW-switch) |

---

## 📁 One folder for all ports (recommended)

Put every game in its own folder inside `sd:/switch/touhou/` — much tidier than a separate folder per game:

```text
sd:/switch/touhou/
    ├── touhou6/     touhou6.nro  + 紅魔郷CM.DAT … (+ bgm/ for music)
    ├── touhou7/     touhou7.nro  + th07.dat, thbgm.dat
    ├── touhou8/     touhou8.nro  + th08.dat, thbgm.dat
    ├── touhou9/     touhou9.nro  + th09.dat, thbgm.dat
    ├── touhou10/    touhou10.nro + th10.dat, thbgm.dat
    └── touhou11/    touhou11.nro + th11.dat, thbgm.dat
```

Add `msgothic.ttc` (from `C:\Windows\Fonts`) to each folder for the original Japanese font; without it the Switch's own Japanese font is used. Each port always checks its own folder first, and older layouts (`sd:/switch/th08/`, `sd:/touhou10/` …) keep working. See each repository's README for the exact files.

*Wonderful Waking World uses its own layout (`sd:/switch/thwww/`) — see its README.*

## 🎮 Same controls in every port

| Nintendo Switch Button | Action |
| :--- | :--- |
| **Left Stick / D-Pad** | Move |
| **B** | Shoot / Confirm |
| **A** | Bomb / Cancel |
| **L / ZL** | Focus (slow movement) |
| **R / ZR** | Skip dialogue |
| **+ (Plus)** | Pause |

These are defaults: each game's own **Key Config** can rebind them, and **Default** there brings this layout back. The D-Pad and sticks only move.

## 🖥 Common features

* 60 FPS on every Switch model, native ARM64 code.
* The 4:3 picture centred with pure black bars (OLED-friendly).
* Original music straight from your game files.
* Japanese title in hbmenu on consoles set to 日本語.
* Saves, replays and scores next to the game data.

---

## 🤝 Credits

* **ZUN / Team Shanghai Alice** — the Touhou Project games.
* **Oligarchomp** — Wonderful Waking World.
* The reconstructions these ports are built on: [GensokyoClub/th06](https://github.com/GensokyoClub/th06), [some100/th07](https://github.com/some100/th07), [YomotsuHisami](https://github.com/YomotsuHisami) (th08, th09, th10, th11) and the [Butterscotch](https://github.com/ButterscotchRunner/Butterscotch) GameMaker runner.
* **Switchbrew & devkitPro** — libnx and the Switch toolchain.
