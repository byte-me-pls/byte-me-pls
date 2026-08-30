## Muhammet Emin Yıldız

C# and C developer. I build engine-adjacent tooling and systems that have to hold up when the
environment stops cooperating — networked games, embedded autonomy, and runtimes small enough to
audit.

Most of what I publish comes out of one habit: when a system is hard to reason about, I'd rather
build the thing that measures it than guess.

---

### 🎮 Unity tooling

| | |
| --- | --- |
| **[stress-lab](https://github.com/byte-me-pls/stress-lab)** | A multi-process load test for FishNet games. Every bot is a separate headless build with its own transport, serializer and GC heap — so the numbers are what a second machine would actually have measured. Found a 16 m spectator desync that solo playtesting could never surface. |
| **[meyzs-toolbag](https://github.com/byte-me-pls/meyzs-toolbag)** | Scene, transform, animation and validation tools collected into one Editor window instead of scattered across menus. |
| **[KnaveFSMSystem](https://github.com/byte-me-pls/KnaveFSMSystem)** | An FSM where states are ScriptableObjects and the entire transition graph is one priority-ordered table — so you can read a character's control flow without opening ten files. |

### 🛰 Systems & embedded

| | |
| --- | --- |
| **[gen-fsm](https://github.com/byte-me-pls/gen-fsm)** | `no_std` Rust state machine whose transition probabilities are evolved by a genetic algorithm. Search runs on the host; the microcontroller only rolls dice against a flat `f32` table. |
| **[alkor-simulation](https://github.com/byte-me-pls/alkor-simulation)** | Rotating Leader consensus over a 4-node LoRa mesh under clock drift, 10% packet loss and EU 868 MHz duty-cycle limits. Built for **TEKNOFEST 2026** with Team OpenPolaris, Gazi University. |
| **[Lammergeier](https://github.com/byte-me-pls/Lammergeier)** | An autonomous drone framework designed so the radio is a detail — Wi-Fi, LoRa, FPV or analog without reworking the stack above it. *Design stage.* |

### 🔒 Language & security research

| | |
| --- | --- |
| **[Horseman-lang](https://github.com/byte-me-pls/Horseman-lang)** | A minimal scripting language and bytecode VM for Trusted Execution Environments. The bet: restrict the language until the runtime is small enough to read in full, and take the loss of generality as the price of an auditable TCB. *Research stage.* |

### 🕹 Game jams

| | |
| --- | --- |
| **[Söz](https://github.com/byte-me-pls/TurkicGameJam-Game)** | A Dede Korkut adventure where every fight is a minigame — a bullet-hell duel or a card battle, played with the cards in your backpack. *Turkic Game Jam 2025.* |
| **[Walking City](https://github.com/byte-me-pls/GoatGameJam)** | A steampunk colony builder on legs. Every room you add is another mouth to feed, and the legs only step while there's steam. |
| **[Fok N Roll](https://github.com/byte-me-pls/midimidi)** | A 12-lane rhythm game played on a real MIDI keyboard. |
| **[Road Trip](https://github.com/byte-me-pls/ankarajam)** | A driving game about remembering. Endless procedural road, roadside events, and a radio that starts silent. *Ankara Game Jam.* |

---

### Working with

`C#` · `C` · `Rust` · `Unity` · `.NET` · `FishNet` · `LoRa` · `embedded`

Interested in networked game architecture, editor tooling, evolutionary methods for control, and
keeping trusted computing bases small.
