# Modular Quake Live Configuration Files
Place `autoexec.cfg` and `thr0ne/` in your `.../Steam/steamapps/common/Quake Live/<steamid64>/baseq3/` directory and `\exec autoexec.cfg` or just restart the game.

## Binds
Open `thr0ne/binds.cfg` and change my binds to your own.
## DPI
Set `m_cpi` to whatever your mouse is using, then use Quake Live's universal sensitivity value type. Example config with `20-21 cm/360`: 
* Mouse DPI = 400
* `seta m_cpi 400`
* `seta sensitivity 20`

## General Features
* Teamnames and enemynames can be enabled and/or disabled for each weapon seperately, and for shoot button held down/let go seperately. `+MOUSE1` is used instead of `+attack`. This alias works together with the script `thr0ne/name.cfg` and the `cg_weaponConfig_*` values in `thr0ne/weapon.cfg`.
* `thr0ne/modkey.cfg` provides a whole bunch of shortcuts on the keyboard that are enabled upon holding `TAB`. Most handy of these features includes changing `s_volume` with the scroll wheel. Upon releasing `TAB`, `thr0ne/binds.cfg` is executed, unbinding and resetting everything. 
* Custom hudfiles specialized for PQL VAMP CLAN ARENA in `thr0ne/ui/`.
