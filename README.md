*IMPORTANT:* This config is set up to function optimally on the _PQL Vamp Community Server_ (`\connect go.pql.lol:27962`). The HUD is configured to not draw armor, ammo or timer elements but this can - of course - be reconfigured by the user (see below).
## Modular Quake Live Configuration Files
Place `autoexec.cfg` and `thr0ne/` in your `.../Steam/steamapps/common/Quake Live/<SteamID64>/baseq3/` directory and `\exec autoexec.cfg` or just restart the game.

### Binds
Open `thr0ne/binds.cfg` and change my binds to your own.
### DPI
Set `m_cpi` to whatever your mouse is using, then use Quake Live's universal sensitivity value type. Example config with `20-21 cm/360`: 
* Mouse DPI = 400
* `seta m_cpi 400`
* `seta sensitivity 20`
`seta m_cpi "0"` to use the default non-cool sensitivity system.

### Highly configurable team/enemynames toggling
Teamnames and enemynames can be enabled and/or disabled for each weapon seperately, and for shoot button held down/let go seperately. `+MOUSE1` is used instead of `+attack`. This alias works together with the script `thr0ne/name.cfg` and the `cg_weaponConfig_*` values in `thr0ne/weapon.cfg`.
### Modifier key
`thr0ne/modkey.cfg` provides a whole bunch of shortcuts on the keyboard that are enabled upon holding `TAB`. Most handy of these features includes changing `s_volume` with the scroll wheel. Upon releasing `TAB`, `thr0ne/binds.cfg` is executed, unbinding and resetting everything. 
### Custom HUD
HUD files specialized for PQL VAMP CLAN ARENA in `thr0ne/ui/`. Each HUD element can be displayed or hidden with the custom `hud_draw*` CVARs. The provided default is intended to be very minimal and unintrusive. For example: `hud_drawAmmo` is set to 0 on all weapons except for `cg_weaponConfig_gl`. (Grenades are the only non-infinite ammo on `go.pql.lol:27962`)

