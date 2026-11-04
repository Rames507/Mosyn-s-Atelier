# Mosyn's Atelier

Draw directly into the Guild Wars 2 world.

A [Raidcore Nexus](https://raidcore.gg/gw2/nexus) addon: lines, shapes,
ranges, arrows and labels that stay where you put them in the world, saved
per map, and shared live with your squad or party if you want.


## Installing

1. Install [Raidcore Nexus](https://raidcore.gg/gw2/nexus).
2. Recommended: install [RealTime API](https://github.com/gwdevcommunity/GW2-RealTime-API-Releases)
   (RTAPI).  
   It is required for terrain detection and sharing drawings with your squad.
   Running without RTAPI works, but with reduced feature set.
3. Download `mosyns_atelier.dll` from this repository and put it into
   `<GW2>/addons/`.
4. Load it in Nexus's addon list.


## Getting started

- `ALT+SHIFT+O` shows the drawing window (tools, colors, line thickness
  and style, Undo, Clear) and the Saves window below it.
- `ALT+SHIFT+D` turns on **Draw mode**, then left click draws in the world.
  Right click still turns the camera.
- Hover a tool's icon for how it works, and the **(?)** next to Draw mode
  for what the mouse and keys do.
- Lines you draw are gone after a reload unless you **Save** them.
- Saves can be copied as text and imported from the clipboard 
  in the Nexus options.
- Saves and folders can be exported as marker packs (`.zip`) for Blish HUD,
  TaimiHUD and TacO, in `<GW2>/addons/MosynsAtelier/exports/` (experimental)

Settings and saves are kept in `<GW2>/addons/MosynsAtelier/`.

## Live sharing

Off by default. Tick **Share drawings with my squad or party** in the
Nexus options, and everyone in your group who did the same sees what the
others draw, as they draw it. It needs RTAPI.

With sharing on, your account name and what you show on your current map
will be sent to the server. The server keeps drawings only in
memory while you're in the room.  
The server saves your account name, addon version, when and how long you were 
connected and how much you sent for 7 days.   
It does not keep IP addresses, your drawings or which squad you were in.

The addon and the server need the same version, the last number aside
(0.2.0 and 0.2.1 work together): if yours is outdated, the status in the
window says so.

## Showcase


https://github.com/user-attachments/assets/2abc984b-acb7-4fbe-ab19-8223069ea226

https://github.com/user-attachments/assets/583068e2-0bcb-43fa-a2ab-40b47d51ea5b

https://github.com/user-attachments/assets/5ef416da-b0a1-4032-b0d5-903b96486515

