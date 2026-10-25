# Touhou Project on Nintendo Switch

![Platform](https://img.shields.io/badge/Platform-Nintendo%20Switch-e60012?style=for-the-badge&logo=nintendoswitch&logoColor=white)
![Ports](https://img.shields.io/badge/Ports-9%20games%20%2B%201%20fangame-8a2be2?style=for-the-badge)

Native homebrew ports of the Touhou Project games for the **Nintendo Switch** (Horizon OS / Atmosphère) — no Linux, Box64 or Wine. Every port runs straight from hbmenu, uses the same controls and can live in one shared folder on the SD card.

> ⚠️ These repositories contain **only the homebrew engine code**. No game files are distributed — you need your own legally owned copy of each game.

---

## ⭐ Official Touhou games — ZUN / Team Shanghai Alice

| | Game | Port version | Download | Source |
| :---: | :--- | :---: | :---: | :---: |
| <img width="96" alt="Touhou 6" src="https://github.com/user-attachments/assets/f7d4ce1a-acb3-49a5-b952-2fae2df142b3" /> | **Touhou 6: the Embodiment of Scarlet Devil**<br>東方紅魔郷 (2002) · needs v1.02h | 1.02h-r2 | [touhou6.nro](https://github.com/saekaze/th06-switch/releases/latest) | [th06-switch](https://github.com/saekaze/th06-switch) |
| <img width="96" alt="Touhou 7" src="https://github.com/user-attachments/assets/d1fed52e-2bad-4d12-acb7-7104aa4129bc" /> | **Touhou 7: Perfect Cherry Blossom**<br>東方妖々夢 (2003) · needs v1.00b | 1.00b-r5 | [touhou7.nro](https://github.com/saekaze/th07-switch/releases/latest) | [th07-switch](https://github.com/saekaze/th07-switch) |
| <img width="96" alt="Touhou 7.5" src="https://raw.githubusercontent.com/saekaze/th075-switch/main/platform/switch/icon.jpg" /> | **Touhou 7.5: Immaterial and Missing Power**<br>東方萃夢想 (2004) · needs ver1.11<br> | 1.11-r1 | [touhou075.nro](https://github.com/saekaze/th075-switch/releases/latest) | [th075-switch](https://github.com/saekaze/th075-switch) |
| <img width="96" alt="Touhou 8" src="https://github.com/user-attachments/assets/57d8c201-1bc7-4ac9-af62-d41f41f9c7e0" /> | **Touhou 8: Imperishable Night**<br>東方永夜抄 (2004) · needs v1.00d | 1.00d-r4 | [touhou8.nro](https://github.com/saekaze/th08-switch/releases/latest) | [th08-switch](https://github.com/saekaze/th08-switch) |
| <img width="96" alt="Touhou 9" src="https://raw.githubusercontent.com/saekaze/th09-switch/main/platform/switch/icon.jpg" /> | **Touhou 9: Phantasmagoria of Flower View**<br>東方花映塚 (2005) · needs v1.50a | 1.50a-r2 | [touhou9.nro](https://github.com/saekaze/th09-switch/releases/latest) | [th09-switch](https://github.com/saekaze/th09-switch) |
| <img width="96" alt="Touhou 10" src="https://github.com/user-attachments/assets/d9c33e0a-3a37-4b76-a2a6-7d73729cd6b7" /> | **Touhou 10: Mountain of Faith**<br>東方風神録 (2007) · needs v1.00a | 1.00a-r5 | [touhou10.nro](https://github.com/saekaze/th10-switch/releases/latest) | [th10-switch](https://github.com/saekaze/th10-switch) |
| <img width="96" alt="Touhou 11" src="https://raw.githubusercontent.com/saekaze/th11-switch/main/platform/switch/icon.jpg" /> | **Touhou 11: Subterranean Animism**<br>東方地霊殿 (2008) · needs v1.00a | 1.00a-r3 | [touhou11.nro](https://github.com/saekaze/th11-switch/releases/latest) | [th11-switch](https://github.com/saekaze/th11-switch) |
| <img width="96" alt="Touhou 12" src="https://raw.githubusercontent.com/saekaze/th12-switch/main/platform/switch/icon.jpg" /> | **Touhou 12: Undefined Fantastic Object**<br>東方星蓮船 (2009) · needs v1.00b | 1.00b-r2 | [touhou12.nro](https://github.com/saekaze/th12-switch/releases/latest) | [th12-switch](https://github.com/saekaze/th12-switch) |
| <img width="96" alt="Touhou 15" src="https://raw.githubusercontent.com/saekaze/th15-switch/main/platform/switch/icon.jpg" /> | **Touhou 15: Legacy of Lunatic Kingdom**<br>東方紺珠伝 (2015) · needs v1.00b<br>⏳ *The first launch is long (it builds the text font once) — after that it's fine.* | 1.00b-r3 | [touhou15.nro](https://github.com/saekaze/th15-switch/releases/latest) | [th15-switch](https://github.com/saekaze/th15-switch) |

## 🌙 Fan games

| | Game | Download | Source |
| :---: | :--- | :---: | :---: |
| <img width="96" alt="Wonderful Waking World" src="https://raw.githubusercontent.com/saekaze/thWWW-switch/main/assets/icon.jpg" /> | **東方眠世界 ~ Wonderful Waking World** by Oligarchomp · needs the free 1.0.1 release from [itch.io](https://oligarchomp.itch.io/wonderful-waking-world) | [thwww.nro](https://github.com/saekaze/thWWW-switch/releases) | [thWWW-switch](https://github.com/saekaze/thWWW-switch) |

---

## 📁 One folder for all ports (recommended)

Put every game in its own folder inside `sd:/switch/touhou/` — much tidier than a separate folder per game:

```text
sd:/switch/touhou/
    ├── touhou6/     touhou6.nro  + 紅魔郷CM.DAT … (+ bgm/ for music)
    ├── touhou7/     touhou7.nro  + th07.dat, thbgm.dat
    ├── touhou075/   touhou075.nro + th075.dat, th075b.dat, th075bgm.dat
    ├── touhou8/     touhou8.nro  + th08.dat, thbgm.dat
    ├── touhou9/     touhou9.nro  + th09.dat, thbgm.dat
    ├── touhou10/    touhou10.nro + th10.dat, thbgm.dat
    ├── touhou11/    touhou11.nro + th11.dat, thbgm.dat
    ├── touhou12/    touhou12.nro + th12.exe, th12.dat, thbgm.dat
    └── touhou15/    touhou15.nro + th15.dat, thbgm.dat
```

Add `msgothic.ttc` (from `C:\Windows\Fonts`) to each folder for the original Japanese font; without it the Switch's own Japanese font is used.

**Touhou 12** also needs its `th12.exe` (the original 1.00b, not a patcher's launcher) in the folder: the port reads the sound and bullet tables from it. Its `scoreth12.dat`, `th12.cfg` and `replay/` are in the PC formats, so you can copy them between the PC and the Switch.

> ⏳ **Touhou 15's first launch takes much longer than usual.** Its text needs Windows fonts that aren't in the game files, so the port builds the font from `msgothic.ttc` (about 7,500 characters in 8 sizes) and saves it as `fontcache/` (~55 MB). Let the loading screen (少女祈祷中) run — every launch after that loads the saved font and is quick.

Each port always checks its own folder first, and older layouts (`sd:/switch/th08/`, `sd:/touhou10/` …) keep working. See each repository's README for the exact files.

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

**Touhou 7.5** is a fighting game: **B** / **A** / **Y** / **X** are its A / B / C / D buttons (weak, strong, spell card, dash; L/ZL and R/ZR also give C and D), **+** pauses. The Joy-Cons are player 1, a Pro Controller player 2.

## 🖥 Common features

* 60 FPS on every Switch model, native ARM64 code.
* The 4:3 picture centred with pure black bars (OLED-friendly).
* Original music straight from your game files.
* Japanese title in hbmenu on consoles set to 日本語.
* Saves, replays and scores next to the game data.

---

## 🤝 Credits

* **ZUN / Team Shanghai Alice** — the Touhou Project games; **Twilight Frontier** — co-developer of Immaterial and Missing Power.
* **Oligarchomp** — Wonderful Waking World.
* The reconstructions these ports are built on: [GensokyoClub/th06](https://github.com/GensokyoClub/th06), [some100/th07](https://github.com/some100/th07), [YomotsuHisami](https://github.com/YomotsuHisami) (th08, th09, th10, th11 — MIT, [confirmed by the author](https://github.com/YomotsuHisami/th10/issues/3)), [SteinsGateON](https://space.bilibili.com/34714121) (th15, MIT, published by [YomotsuHisami](https://github.com/YomotsuHisami/th15); th075, MIT, published by [Goan114](https://github.com/Goan114/th075)), [Tweet-META](https://github.com/Tweet-META/th12) (th12, MIT, also published by [Ritosa2333](https://github.com/Ritosa2333/th12)) and the [Butterscotch](https://github.com/ButterscotchRunner/Butterscotch) GameMaker runner.
* **[シエル](https://github.com/kan8223-dotcom/th10-psp-native)** (native PSP ports of Touhou) — worked out how the PC game builds its 少女祈祷中 loading screen and shared the code from their TH15 PSP port; Touhou 15 uses it since 1.00b-r3.
* **Switchbrew & devkitPro** — libnx and the Switch toolchain.
