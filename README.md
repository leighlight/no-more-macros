# No More Macros
 
An interactive ACT/OverlayPlugin overlay for tracking mechanic as if you are using a macro in FFXIV ultimates and savage fights. Made this because I want to clean up my macros a little bit. I based this on the WTFDIG helpers as an alternative for people who dont wanna leave their game window. 
 
**Current version:** v0.1.0 
Includes Dancing Mad (Ultimate) p4 
M12Sp2 Idyllic dream, basic version 

## Setup (ACT / OverlayPlugin)
 
1. Make sure you have **ACT**, **FFXIV_ACT_Plugin**, and **OverlayPlugin** installed.
2. In OverlayPlugin, click **New** and choose a **General** overlay.
3. Set the URL to:
```
   https://leighlight.github.io/no-more-macros/
```
4. Turn **click-through OFF** for this overlay — you need to be able to click the buttons.
5. Resize and reposition it wherever it won't block your view of the arena.
6. Use the **Fight** dropdown at the top of the overlay to pick your current fight.
7. Toggle the **Hide/Show Panel** button yourself when the mechanic starts/ends — there's no auto phase-detection yet (see Known Limitations).

## Future features planned maybe idk
Automatic fight detection ( this will make it reliant on ACT updates as currently it is not reliant, will deliberate on more later) 
Making it more modular to people can add presets themselves or different strats, currently it just works for NA DN uptime for Idyllic dream for instance. 


## Changelog
 
- **v0.1.0** — Initial public version. DMU P4 fully built (Exdeath/Chaos Real/Fake tracking, Accel Bomb exclusivity, Mana Charge/Release XNOR). Idyllic Dream stub added (clone tether, tether pickup zones). Custom dropdown to work around OverlayPlugin's CEF not rendering native `<select>` popups.