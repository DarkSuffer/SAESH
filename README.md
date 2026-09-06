# 🥚 Steal An Egg — Server Finder | Log `v1.0.3`

> **Dev:** `@jo_2527`  
> **Keybind:** `RightShift` *(Customizable in Settings)*  

***

### ⚙️ Engine & Hop Persistence
- **Parallel Scan Engine:** 2x faster scanning (fetches 2 API pages concurrently).
- **120s JobId Blacklist:** Automatically skips full or broken servers on retries.
- **Cross-Server Auto-Load:** UI & Auto-Exec persist across hops/rejoins (`queue_on_teleport`).
- **Auto-Retry Queue:** Seamlessly tries next best server (`#1➔#2➔#3`) if target is full.
- **Anti-Freeze Guard:** 8s HTTP timeout + exponential 429 rate-limit backoff.

### 🎨 UI & Design Fixes
- **No More UI Clipping:** Fixed Settings tab overflow & border clipping on all screen sizes.
- **Header Alignment:** Rebuilt `X`, `-`, and ⚙️ controls with vector frames (no glitched text).
- **Mobile Responsive:** Dynamic auto-scaling (`UIScale`) with non-sticky touch dragging.
- **SS-H Terminal:** Minimized console pill features a blinking command cursor (`> SS-H █`).

### 📜 Script Hub & Auto-Exec
- **Ranked Catalog:** `#1 Clover Hub`, `#2 Fyy Community`, `#3 Big Froot` *(All Working)*.
- **Speed Hub Section:** Dedicated section divider hosting `#1 Speed Hub X`.
- **1-Click Auto-Exec:** Toggle `AUTO-EXEC` on main tab + 3 custom modes in Settings.
- **Custom Keybinds:** Set any key in Settings to minimize/restore with auto-save config.
- **JobId & Join Link Copier:** Instant 1-click clipboard copy for server JobIds & deep links.

***

```text
[+] Parallel 2-Page API Fetching (2x speedup)
[+] 120s JobId Blacklist & Retry Queue
[+] Cross-Server Auto-Persist (queue_on_teleport)
[+] Custom Keybind Selector & Auto-Save Config
[+] SS-H Blinking Terminal Console Cursor
[+] Fixed Settings Tab Overflow & UI Clipping
[+] Fixed Header Icon Misalignment & Missing Glyphs
[+] Fixed 0-Player Ghost Server & Full Teleport Errors
```
