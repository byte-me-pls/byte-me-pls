<h1 align="center">Muhammet Emin Yıldız</h1>

<p align="center">
  <b>C# · C · Rust</b><br>
  <sub>Networked game internals, embedded autonomy, and runtimes small enough to audit.</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust" />
  <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet" />
</p>

---

<p align="center">
  <i>When a system is hard to reason about, I'd rather build the thing that measures it than guess.</i>
</p>

---

### 🎮 Unity

**[stress-lab](https://github.com/byte-me-pls/stress-lab)** — Multi-process load testing for
FishNet. Every bot is a separate headless build with its own transport, serializer and GC heap, so
the numbers are what a second machine would actually have measured.
<br>→ *Caught a **16 m** spectator desync that solo playtesting could never surface.*

**[meyzs-toolbag](https://github.com/byte-me-pls/meyzs-toolbag)** — Every scattered editor utility,
collected into one window.

**[KnaveFSMSystem](https://github.com/byte-me-pls/KnaveFSMSystem)** — States are ScriptableObjects,
the whole transition graph is one priority-ordered table. Read one method, you've read the character.

### 🛰 Systems & embedded

**[gen-fsm](https://github.com/byte-me-pls/gen-fsm)** — `no_std` Rust state machine whose transitions
are *evolved* by a genetic algorithm. Search runs on the host; the MCU just rolls dice against a flat
`f32` table.

**[alkor-simulation](https://github.com/byte-me-pls/alkor-simulation)** — Rotating Leader consensus
on a LoRa mesh under clock drift, 10% packet loss and EU 868 MHz duty-cycle limits.
<br>→ *TEKNOFEST 2026 · Team OpenPolaris, Gazi University*

**[Lammergeier](https://github.com/byte-me-pls/Lammergeier)** — Drone framework designed so the radio
is a detail. *Design stage.*

### 🔒 Research

**[Horseman](https://github.com/byte-me-pls/Horseman-lang)** — A language and bytecode VM for Trusted
Execution Environments. The bet: restrict the language until the runtime is small enough to read in
full, and take the loss of generality as the price of an auditable TCB.

### 🕹 Jams

**[Söz](https://github.com/byte-me-pls/TurkicGameJam-Game)** — Dede Korkut adventure; every fight is a
different game · **[Walking City](https://github.com/byte-me-pls/GoatGameJam)** — steampunk colony
builder on legs · **[Fok N Roll](https://github.com/byte-me-pls/midimidi)** — rhythm game on a real
MIDI keyboard · **[Road Trip](https://github.com/byte-me-pls/ankarajam)** — a driving game about
remembering

---

<p align="center">
  <sub>networked game architecture · editor tooling · evolutionary control · small trusted computing bases</sub>
</p>
