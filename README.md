# Venta virtual office

One web page showing a 3D office: a walkway with reception, rooms for Chief of Staff, Sales, Operations and Marketing, a conference room and a lounge. Click a room or person (or the buttons below) to fly in and see what that agent does and the command to paste into Claude Code. Coming-soon agents sit at dark screens. Drag to look around, scroll or pinch to zoom, and press **Whole office** to zoom back out.

## Open it

In Terminal, from anywhere:

```bash
open ~/Documents/GitHub/venta-office/app/index.html
```

It opens in your normal browser. It needs internet only to load the 3D library and the Inter font (both free). No account, no keys, no server. It never sends email or connects to Google; it only shows commands for you to copy.

## When an agent goes live

In `index.html`, find the `AGENTS` list near the top of the script. For that agent, change `live:false` to `live:true` and add its command, for example `cmd:'/prospect'`.
