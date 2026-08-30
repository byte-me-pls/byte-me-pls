<p align="center">
  <img src="assets/hero.svg" alt="Muhammet Emin Yıldız — networked game internals, embedded autonomy, runtimes small enough to audit" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET" />
</p>

<p align="center">
  <i>When a system is hard to reason about, I'd rather build the thing that measures it than guess.</i>
</p>

<br>

<h3 align="center">⭐ Featured</h3>

<table width="100%">
<tr><td valign="top">
  <h3>🧪 <a href="https://github.com/byte-me-pls/stress-lab">stress-lab</a> &nbsp;<img src="https://img.shields.io/badge/Unity-000?style=flat-square&logo=unity" align="top" />&nbsp;<img src="https://img.shields.io/badge/FishNet-1f6feb?style=flat-square" align="top" /></h3>
  <p><b>Multi-process load testing for FishNet games.</b> The Editor hosts; every bot is a separate headless build with its own transport, serializer, player loop and GC heap — so what comes back is what a second machine would actually have measured, not what a bot swarm sharing your Play Mode session can show you.</p>
  <table>
    <tr><th align="left">Largest bone jump a spectator saw</th><th align="right"></th></tr>
    <tr><td>Snapshot replay @ 20 Hz</td><td align="right"><b>0.26 m</b></td></tr>
    <tr><td>Observer-side simulation @ 5 Hz</td><td align="right"><b>16.45 m</b></td></tr>
  </table>
  <p><sub>Same scene, same players, one changed setting. The regression only existed on machines watching <i>someone else</i> fall — so it survived every session of solo playtesting.</sub></p>
</td></tr>
</table>

<br>

<h3 align="center">🛠 Tooling &nbsp;&&nbsp; Systems</h3>

<table width="100%">
<tr>
<td width="50%" valign="top">
  <h4>🎛 <a href="https://github.com/byte-me-pls/KnaveFSMSystem">KnaveFSMSystem</a></h4>
  <p>States are ScriptableObjects; the whole transition graph is one priority-ordered table. Read one method, you've read the character.</p>
  <p><code>C#</code> <code>Unity</code> <code>zero-alloc</code></p>
</td>
<td width="50%" valign="top">
  <h4>🧰 <a href="https://github.com/byte-me-pls/meyzs-toolbag">meyzs-toolbag</a></h4>
  <p>Every scattered editor utility — scene, transform, animation, validation — collected into one window instead of five menus.</p>
  <p><code>C#</code> <code>Unity Editor</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <h4>🧬 <a href="https://github.com/byte-me-pls/gen-fsm">gen-fsm</a></h4>
  <p><code>no_std</code> Rust state machine whose transitions are <i>evolved</i> by a genetic algorithm. Search runs on the host; the MCU just rolls dice against a flat <code>f32</code> table.</p>
  <p><code>Rust</code> <code>no_std</code> <code>embedded</code></p>
</td>
<td width="50%" valign="top">
  <h4>📡 <a href="https://github.com/byte-me-pls/alkor-simulation">alkor-simulation</a></h4>
  <p>Rotating Leader consensus on a 4-node LoRa mesh under clock drift, 10% packet loss and EU 868 MHz duty-cycle limits.</p>
  <p><sub>🏆 <b>TEKNOFEST 2026</b> · Team OpenPolaris, Gazi University</sub></p>
  <p><code>.NET 9</code> <code>Ed25519</code> <code>LoRa</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <h4>🔒 <a href="https://github.com/byte-me-pls/Horseman-lang">Horseman</a></h4>
  <p>A language and bytecode VM for Trusted Execution Environments. The bet: restrict the language until the runtime is small enough to read in full, and take the loss of generality as the price of an auditable TCB.</p>
  <p><code>SGX</code> <code>TrustZone</code> <img src="https://img.shields.io/badge/research-8957e5?style=flat-square" align="top" /></p>
</td>
<td width="50%" valign="top">
  <h4>🦅 <a href="https://github.com/byte-me-pls/Lammergeier">Lammergeier</a></h4>
  <p>An autonomous drone framework designed so the radio is a detail — Wi-Fi, LoRa, FPV or analog without reworking the stack above it.</p>
  <p><code>UAV</code> <code>embedded</code> <img src="https://img.shields.io/badge/design%20stage-orange?style=flat-square" align="top" /></p>
</td>
</tr>
</table>

<br>

<h3 align="center">🕹 Game Jams</h3>

<table width="100%">
<tr>
<td width="50%" valign="top">
  <h4>⚔️ <a href="https://github.com/byte-me-pls/TurkicGameJam-Game">Söz</a></h4>
  <p>A Dede Korkut adventure where every fight is a different game — a bullet-hell duel or a card battle, played with whatever's in your backpack.</p>
  <p><sub>Turkic Game Jam 2025</sub></p>
</td>
<td width="50%" valign="top">
  <h4>🦿 <a href="https://github.com/byte-me-pls/GoatGameJam">Walking City</a></h4>
  <p>A steampunk colony builder on legs. Every room you add is another mouth to feed, and the legs only step while there's steam.</p>
  <p><sub>Game jam</sub></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <h4>🎹 <a href="https://github.com/byte-me-pls/midimidi">Fok N Roll</a></h4>
  <p>A 12-lane rhythm game played on a real MIDI keyboard. No controller? A tracker layout gets you charting anyway.</p>
  <p><sub>Midi Midi Bir Kuş</sub></p>
</td>
<td width="50%" valign="top">
  <h4>🛣 <a href="https://github.com/byte-me-pls/ankarajam">Road Trip</a></h4>
  <p>A driving game about remembering. Endless procedural road, roadside events, and a radio that starts silent — you have to turn it up yourself.</p>
  <p><sub>Ankara Game Jam</sub></p>
</td>
</tr>
</table>

<br>

<p align="center">
  <sub>networked game architecture &nbsp;·&nbsp; editor tooling &nbsp;·&nbsp; evolutionary control &nbsp;·&nbsp; small trusted computing bases</sub>
</p>
