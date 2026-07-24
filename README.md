# PGR4-Decomp [TESTING BRANCH]
This project intends to decompile (and eventually port to pc) Project Gotham Racing 4.
a Compiled .EXE has been provided in this branch, however you need to provide your own game files (dump it as an ISO, then use XEX tool to extract and decrypt (if needed))
### Please note:
This project is VERY early in its progress, however updates are quite frequent!
## Current **known** issues
* Pre-AVX2 Machines can't run this at the moment (a DLL should be able to fix this)
* NVIDIA Cards (or at least, mine) have some graphical issues

## Current Progress
- [x] GOD Files
- [x] C++ Converted files
- [X] Launchable EXE (on AVX2+ hardware, non AVX2 capable hw in testing)
- [ ] Installer EXE (provide your own files)
### Optional features
- [ ] Adjustable graphics settings
- [ ] Online (unlikely)
- [ ] Mod Support (equally as unlikely as online) 
## Notes
* This is a ONE person effort at the current moment in time, commits will NOT be frequent.
* ANY help is appreciated greatly, feel free to contribute to this project!
## Credits
* [ReXGlue SDK](https://github.com/rexglue/rexglue-sdk) - For allowing C++ to be generated AHEAD
* Tera in the ReXGlue Discord - For allowing me to pick up from where they left off with ReXGlue
* xextool - For allowing me to extract my XEX from a dumped ISO (seriously, that was a LIFE saver)

