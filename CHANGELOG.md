# Changelog

All notable changes to the Hackfest beta.

## v0.18.0-beta — 2026-07-16
### Changed
- **All-new phone.** The in-game phone is a real smartphone now instead of a plain window: a rounded
  handset with a status bar (a live in-fiction clock, carrier, signal, wifi and battery), a gradient
  wallpaper, a home screen with a big clock widget and a dock, and a home bar to put it away. Every app
  has a clean, hand-drawn icon — shopping cart, chat bubble, handset, pirate flag, coin, gear — instead
  of the old emoji tiles, and Messages reads like a proper chat with sender, timestamp and rounded bubbles.

## v0.17.0-beta — 2026-07-16
### Added
- **Free demo.** The in-browser build and a keyless Windows download are now a **demo** — play the
  opening act (build a rig, break into CorpoMax, take down Brant) and the story walls with a prompt to
  grab the full game. The full campaign is the paid download.
- **All-new visual PC builder.** The tower builder is a real, motherboard-style scene now: pick a case
  first, drop a board into the open case, then seat parts into actual sockets — a CPU socket with VRM
  heatsinks, a DIMM bank, long PCIe graphics-card slots, a chipset, a drive cage and a PSU shroud, with
  the monitor on the desk. Empty slots show a ghost of the part that belongs there and a small "+".
- **Every case, monitor and RGB kit looks unique.** Cardboard looks like cardboard, glass is
  see-through, steel is brushed metal, the Titan is gold, the rack has rack ears — and each monitor has
  its own chassis (bulky CRT, thin OLED, ultrawide…). Installed RGB kits **light up and animate** in
  their own zones (a strip, the case loop, fan halos, underglow, an infinity mirror…).
### Changed
- **Realistic motherboard slots.** Boards top out at 2 CPU sockets / 8 RAM / 4 PCIe / 6 drives, like
  real hardware, and every board is visibly different from the last.

## v0.16.1-beta — 2026-07-15
### Fixed
- **Web build: the last blank icons now render.** The phone/window **✕** close, the **✓** on
  "Owned", the **☰** menu, the **⊞** start button, the **↺** Load arrow (and assorted arrows,
  the trace bar, and the RipCoin mark) were still showing as blank boxes in the browser — the
  previously-bundled symbol font didn't actually contain any of them. Swapped in a broad
  symbol font that covers them all; color emoji still render in colour.
- **Crapazon delivery is now centered.** The "Delivered" box was opening pinned to the top-left
  corner instead of the middle of the screen. It now sits dead-center.

## v0.16.0-beta — 2026-07-15
### Changed
- **Deliveries open straight to the parts screen.** The order now unpacks onto one centered screen,
  dropping each item in every half-second; **Add to Inventory** unlocks once every item has arrived.
### Fixed
- **Web build now renders all the icons/symbols.** Bundled proper emoji + symbol fonts, so the phone,
  menu, and store icons (the ✕, checkmarks, +/−, arrows, spinner, etc.) display in the browser instead
  of showing blank.
- **A branded loading screen** now shows while the web build downloads, instead of the default engine logo.

## v0.15.0-beta — 2026-07-14
### Changed
- This build now requires a **product key** to activate on first launch.
- Hardened, self-contained packaging.
### Fixed
- **Crapazon deliveries now open correctly** — the parts box was failing to reveal your order.

## v0.14.0-beta — 2026-07-14
### Added
- **A real studio splash.** "Devious Developments" (with devil-horned D's) holds, fades to the
  **HACKFEST** title, then boots to the menu. Click or press a key to skip.
- **Crapazon deliveries.** Purchases now ship as a package — a 📦 on the right of the screen. Open it
  to watch each part unbox one at a time, then **Add to Inventory**. Parts aren't usable until they're
  unboxed. Every product type has its own icon.
- **Sell your old hardware.** Crapazon has a **Sell** tab — offload spare parts from your inventory for
  50% of list price.
- **Auto-Build.** One button on the PC Tower picks your best motherboard, fills every slot with the
  strongest parts you own, sizes the PSU to the load, and flags anything missing or underpowered.
- **Message timestamps.** Texts now carry an in-fiction time, so the thread reads like a real phone.
### Changed
- **Objectives update instantly.** The moment an action lands — a message read, a purchase, a crack
  finishing — the objective updates, instead of waiting for a window to close.
- **The intro no longer double-prompts.** The opening ends on **Continue**; the objective card owns the
  single "Open Phone" button.
- **The phone stays on-screen.** It can no longer be dragged under the taskbar or off the edge, and it
  always fits the screen.
- **Crapazon rows are colour-coded** — green = owned, yellow = available, grey = locked.

## v0.13.2-beta — 2026-07-14
### Fixed
- **The game launches again.** The previous build could fail to start with a “missing `.pck`”
  prompt on some machines — the packaged game data was being corrupted while the app icon was
  stamped onto the executable. The icon is now embedded without touching the game data.
### Changed
- **Proper app icon at every size.** `Hackfest.exe` now shows the terminal `>_` icon in Explorer,
  the taskbar, and when imported into Steam, instead of falling back to the default icon at small
  sizes.

## v0.13.1-beta — 2026-07-13
### Fixed
- **RipStore no longer stretches off the screen.** A long software description (the AntiVirus listing)
  was blowing out the store's width; every listing now wraps cleanly.
### Changed
- **Buying software shows a proper download.** Purchases now play a live download screen — progress
  bar, countdown, and a scrolling transfer terminal — instead of a silent “…”, matching the rest of
  the ops.

## v0.13.0-beta — 2026-07-13
### Added
- **Achievements / Trophies — 24 of them.** Earn them by playing, and most grant a small
  **permanent bonus that stacks**: faster cracks and ops, more income, a quieter trace, extra
  connections, more storage headroom, or faster leveling. Campaign milestones pay **one-time
  bounties** — cash, RipCoin, even free zombie boxes. A new **🏆 Trophies** app (Start menu) tracks
  them all: unlocked trophies show the bonus they granted, locked ones show the goal to chase, and a
  few stay **secret** (“???”) until you earn them. Unlocking one pops a little gold celebration, and
  loading an older save awards anything you'd already qualified for.

## v0.12.0-beta — 2026-07-13
### Added
- **Install and upgrade an operating system.** Boot media is a real step now: start with an
  **All-in-One Boot Drive** (OS preinstalled) from Crapazon, or build a custom **HackfestOS** at the
  new in-OS **OS Builder** — image a blank USB flash (with an imaging puzzle), install it to a drive
  in the tower, or **clone** it to a bigger drive before you swap. Each OS tier grants **more
  connections, faster ops, more income, a quieter trace, and extra storage**. Pull the drive your OS
  lives on and you'll have to reinstall it.
- **Six malware types, each paid by different hardware** — **Adware** (RAM, quiet), **Botnet Node**
  (bandwidth), **CryptoMiner** (GPU → RipCoin, but loud), **Data Scraper** (fills the disk, then sells
  the dump), and **Ransomware** (one huge payout, then the box is bricked) join the reworked Spam and
  Torrent bots.
- **Antivirus** — buy your own to cool your trace faster and harder; hardened target boxes now run
  their own AV that logs an extra intrusion line when you drop malware (groundwork for a future
  hacker-vs-hacker layer).
- **HostResolver is its own tool**, and **scanning the net farms zombies** — sweep for a while to
  enslave a fresh weak box with no crack required.

### Changed
- **Malware income now scales with the victim's hardware, not yours.** Every enslaved box runs on its
  own rig — a beefy server pays far more than an intern's laptop — and each malware keys off a
  different stat (Spam = CPU/RAM, Torrent = bandwidth/drive, and so on). Your rig shrinks *your* op
  times; the zombie's rig sets *its* yield.
- **Every download is a timed transfer over your NIC** — even buying software from RipStore. Faster
  network cards pull it down quicker, and downloads in flight reserve their disk space so you can't
  over-commit the drive.
- **Resolving a target is a short timed lookup** now, gated on owning the HostResolver.

### Fixed
- Realigned the automated test suite to the new systems and added coverage for the OS install model.

## v0.11.0-beta — 2026-07-12
### Added
- **Every box is now a tabbed workspace** — a cracked target opens into **Info** (access, malware,
  the staff who log in from home), **Logs** (scrub the trail), and **Files** (the encrypted loot),
  instead of one long scroll.
- **Uninstall software** — a 🗑 button in the Software app frees the drive space it was using
  (running zombies keep their copy). No more hoarding old crackers you can't delete.
- **Hide the objective** — close the objective panel with ✕ and reopen it any time from
  **Start → Objective**.
- **Locked-tier teasers in Crapazon** — you can see the gear coming and what unlocks it (🔒 Act N).

### Changed
- **Hardware scaling reworked around the story.** Gear now unlocks **a quarter of the catalog per
  act** — the low tiers to start, the top gear only near the end — so every upgrade is earned and
  the numbers actually matter. Lots **more parts** with proper names (CPUs, GPUs, drives, PSUs, NICs,
  boards, coolers), spread across the whole campaign.
- **Motherboards now have NIC slots** — early boards hold just **one NIC** (no stacking cards for
  cheap connections); you earn more connections from better single NICs, and multi-NIC boards later.
- **A smoother storage curve** — a new mid-size drive tier means the SSH ladder pushes you up drives
  gradually, and the rainbow tables force the big drive right when the banks need it.
- **Dirty logs no longer block you — they get you caught.** You can install malware over an
  unscrubbed log, but **every action leaves a log line** (login, upload, download), and each
  incriminating line raises your **exposure** — the counter that feeds the trace. Leave a mess and
  security finds you. (Only logging out leaves no trace.) A malware **upload** now leaves its own log
  line, and installs show which **version** you're dropping.

### Fixed
- **Arc 2 could dead-end.** After finishing the CorpoMax arc there were no targets left to act on, so
  the story couldn't advance — CorpoMax HQ now opens up as intended.
- **Cipher puzzles were always the same rotation** (the random seed wasn't being set) — they're
  properly randomized now.
- **Mercy's rep-store tools** (Aquawall, HashBreaker, Rainbow Tables) could wrongly show up for sale
  in RipStore — they're rep-only again.
- The Crapazon motherboard slot legend moved into a hover tooltip instead of cluttering every row.

## v0.10.0-beta — 2026-07-12
### Added
- **A full story campaign, start to finish** — beyond the CorpoMax arc: get traced and learn to
  disappear, break into **CorpoMax HQ**, follow the money through the **banks**, and hunt the one
  who was above it all. It has an ending now.
- **Contacts & jobs** — a new Contacts app. Fixers (Echo, Mercy, Torch) post contracts that pay
  **cash, reputation, and free zombie boxes**. Jobs run on a timer and draw heat while they run.
- **Detection & tracing** — live connections now heat a **trace meter**. Let it fill and security
  follows you home: your **IP is burned** and every session drops. Buy a fresh identity with
  **reputation** (your first reset is free) and get back to work.
- **The rep store (Mercy)** — spend reputation, not RipCoin, on gear you can't buy anywhere else —
  including **Aquawall**, which softens firewalls so cracks bite faster.
- **New crack types** — not everything speaks SSH. **Hash** and **Rainbow** locks need their own
  looted cracker families (rainbow tables are enormous — mind your disk), plus a universal
  **Brute Forcer** for low-tier boxes.
- **Coolers** — a new optional rig part. A colder rig runs quieter on the wire: better coolers slow
  how fast a live trace heats up while you're connected.
- **Four more puzzle kinds** — binary convert, hex decode, pattern match, sort sequence (12 total).
### Changed
- **NICs are now required to boot** (you can't hack anything offline) — and if you can't afford one,
  the builder gives you a free basic NIC so you're never stuck.
- **Slower XP curve** so idle money can't out-level you.
- **Bigger software footprints** (looted crackers, and especially rainbow tables) and **higher
  component wattage** — you'll upgrade drives and PSUs more often.
- **Jobs and the story** now introduce new systems (the rep store, banks, tracing) in context,
  through characters, instead of tutorials.

## v0.9.0-beta — 2026-07-12
### Added
- **Network cards (NICs)** — a new rig part on Crapazon. Your NICs set how many targets you can
  attack **at once** (connections) and your **upload/download speed**. Better fiber = more parallel
  hacks and faster payload uploads / loot downloads.
- **Two-stage malware install** — dropping malware now **uploads** the payload (NIC-bound) and then
  **installs** it (compute-bound), each with its own timer.
- **Manual IP resolver (HackFple)** — hosts named in a cracked box's log no longer add themselves.
  Read the log, copy an IP, and **resolve it in Browser → HackFple** to add it to your Targets.
- **In-game Notepad** — a saved scratchpad (📝 on the taskbar) for IPs, passwords, and ladder notes.
- **Animated operation screens** — cracking, scanning, uploading, installing, and log rewrites now
  show a live countdown, a progress bar, and a scrolling terminal.
- **Stacked level-ups** — cross several levels in one collect and you'll see **each** level in turn,
  with an **OK** button and the list of hardware that level unlocked.
- **Multi-buy on Crapazon** — a quantity stepper lets you add several of the same part to your cart.
- **Item help** — hover any Crapazon listing for a description; motherboards now spell out what the
  **c / r / g / s / p** slot counts mean.
- **Admin/debug panel** (Start menu) — add cash / RipCoin / levels and instantly finish op timers
  while testing.
### Changed
- **Connections are now driven by your NICs**, not your CPU count.
### Fixed
- **Connection monitor** no longer grows behind the Hardware Monitor — the right-side panels stack.
- **Zombie / target lists** now scroll when they get long.
- **Save Game dialog** now centers on screen.
- **TaskMon** lists only active operations (running spam/torrent bots live in the Cashflow monitor).

## v0.8.1-beta — 2026-07-12
### Added
- **Puzzle gauntlet** — 8 mini-puzzle kinds (cipher lock, CAPTCHA retype, odd-one-out, password
  recovery, code-breaker, sequence match, math gate, anagram). Every box you crack throws a random
  captcha; encrypted loot files guard the best software behind a harder puzzle.
- **Employees via logs** — cracking a company server writes its internal **[service]** hosts and
  **[user]** employees into its auth log; trace them to open up the network. CorpoMax's own log now
  seeds the whole arc (no more "here's a list of IPs").
- **Real timeline** — operations take real time, scaled by your rig: minimum hardware means a
  ~5-minute crack and a 30-second log rewrite, dropping fast as you upgrade CPUs/GPUs.
- **Parallel operations** — the number of simultaneous connections equals your installed CPU count,
  so multi-CPU boards let you crack/scan several boxes at once. New always-on **connection monitor**
  (top-right) and a **Cashflow monitor** widget.
- **In-OS rig upgrades** — power down from the Start menu to open the tower, swap in bigger drives /
  more CPUs, and boot back up.
### Fixed
- **Text puzzles rejecting correct answers** (the math gate especially) — an input-capture bug meant
  submits silently failed.
- **Save/Load dialog and puzzles** now center properly on screen.
- **Desktop wallpaper text** no longer hides behind the taskbar.

## v0.8-beta — 2026-07-11
### Added
- **Full CorpoMax arc** — the fired-from-CorpoMax intro, ordering parts and building a PC, booting
  into **HackfestOS**, buying software with RipCoin, and the resolve → scan → crack → malware →
  zombie → collect loop.
- **The SSH cracker ladder (v1.0 → v2.0)** — firewalls climb by minor version; loot the next
  cracker from an employee box before you can break the next one, up to the CorpoMax boss.
- **Hardware & rig building** — motherboards, CPUs/GPUs/RAM, storage, PSUs, monitors, cases, fans;
  a power-draw vs. supply gate and a storage economy that forces drive upgrades as you grow.
- **XP & leveling** that unlocks better hardware tiers.
- **HackfestOS shell** — wallpaper, taskbar, Start menu, an in-OS browser (CoinSwap + RipStore),
  Targets app, an editable auth-log ("cover your tracks"), and desktop monitor widgets.
- **Branding** — custom app/exe icon, animated splash, neon main menu; standalone Windows build.
