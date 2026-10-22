**Project IGI Studio 2.0.0 — Windows** (works on Windows 10 and 11)

| File | For | What it is |
|---|---|---|
| `IGI-Studio-Setup-2.0.0-Windows64bit.exe` | 64-bit Windows (most PCs today) | full installer |
| `IGI-Studio-Portable-2.0.0-Windows64bit.zip` | 64-bit Windows | portable — unzip and run, no install |
| `IGI-Studio-Setup-2.0.0-Windows32bit.exe` | **32-bit Windows** (older laptops) | full installer for 32-bit |

How to tell which you need: Settings → System → *Device specifications* → "System type".

- "64-bit operating system" → use the **Windows64bit** files
- "32-bit operating system" → use the **Windows32bit** file

Every build includes the built-in OpenCode AI chat. On a 32-bit machine the AI runs
through the relay automatically (the studio installs Tailscale by itself the first time).
