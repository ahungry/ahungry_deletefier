// LPF = LAUNCH_PATCH_FUNCTION
// COPY_EXISTING_REGEXP GLOB ~^.+\.cre$~ ~override~
//  PATCH_IF RANDOM(1 100) <= %del_per% BEGIN
    // LPF DELETE_CRE_ITEM STR_VAR item_to_delete = "shld.+" END
    // LPF DELETE_CRE_ITEM STR_VAR item_to_delete = "sw2h" END

    // LPF DELETE_CRE_ITEM STR_VAR item_to_delete = "sw2h02\|sw2hdeat\|_?sw2h05\|ringdemn\|_?shld06" END
    // LPF DELETE_CRE_ITEM STR_VAR item_to_delete = ".*" END

    // https://weidu.org/WeiDU/README-WeiDU.html#ADD_CRE_ITEM
    // ADD_CRE_ITEM ~STAF01~ #0 #0 #0 ~IDENTIFIED~ ~WEAPON1~ EQUIP
// END
// BUT_ONLY_IF_IT_CHANGES
