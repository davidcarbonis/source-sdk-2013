Freeman's Mind edits
* No player blood
  *  sp/src/game/server/player.cpp L948-959
* Demo recording bug fix
 * sp/src/game/client/c_baseentity.cpp L5897-5906

Personal edits
* Rain on all surfaces
  * sp/src/game/client/c_effects.cp L348-362
* Parallax Corrected Cubemaps - https://developer.valvesoftware.com/wiki/Parallax_Corrected_Cubemaps
  * sp/src/utils/vbsp/matrixinvert.h - Added
  * sp/src/utils/vbsp/cubemap.cpp - Updated as above
  * sp/src/utils/vbsp/vbsp.h - Updated as above
  * sp/src/utils/vbsp/map.cpp - Updated as above