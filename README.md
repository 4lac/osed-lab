# OSED Lab

A single-file, offline HTML tool I built to practice Windows exploit development (OSED-style topics: DEP, ASLR, SEH, ROP) on 32-bit lab targets.

No install, no server, no network calls. Open `index.html` in a browser.

**Live page:** https://4lac.github.io/osed-lab/

## Tools

| Tool | Purpose |
|---|---|
| ASLR Calculator | Work out addresses from a module base and offsets |
| Shellcode Builder | Assemble shellcode for practice |
| Payload Builder | Put together an overflow payload |
| PE Scanner | Inspect PE files and flag risky imports |
| ROP Builder | Plan ROP chains (VirtualAlloc / WriteProcessMemory) |
| WinDbg Cheatsheet | Quick command reference |
| Bad Char Tracker | Track bad characters while testing |

Default setup: Windows Server 2019 x86, DEP and SEHOP on, WinDbg only (no mona.py).

## Usage

Download or clone the repo, then open `index.html`.

## Disclaimer

For education and for practice in lab environments you own or are authorised to test. Don't use it against systems without permission.

## Author

Reyof — [github.com/4lac](https://github.com/4lac)
