--[[-------------------------------------------------------------------------
Enable or disable the usage of the M9K weapon packs.

To use this, make sure that the server has installed all of the required addons.
Players also need to download the addons, but as a dedicated server owner I 
expect you to know how this works.

Required addon IDs:
- 144982052
- 128089118
- 128091208
- 128093075

NOTE: If you disable this, the weapons in the pre-made weapon list won't work!
---------------------------------------------------------------------------]]
GG_USE_M9K = false

--[[-------------------------------------------------------------------------
Enable or disable the usage of MW2 playermodels.

To use this, make sure that the server has installed the required addon.
Players also need to download the addon, but as a dedicated server owner I 
expect you to know how this works.

Required addon ID:
- 500247187

NOTE: If you disable this, the skins in the pre-made skins list won't work!
---------------------------------------------------------------------------]]
GG_USE_MW2_SKINS = false

--[[-------------------------------------------------------------------------
This is the list with weapons used during the game. You can edit the list if
you want to use different weapons. Keep in mind that the all slots have to
be filled and that you can't have more than 20 weapons in the list.

Note: If somehow the weapons in the list below don't work, the back-up
weapons list will be used instead.
---------------------------------------------------------------------------]]
GG_WEAPONS_LIST = {
	{ weapon = "arc9_cod2019_pi_357", ammo = 30 }, -- revolver
	{ weapon = "arc9_cod2019_pi_m1911_akimbo", ammo = 60 }, -- M1911 akimbo
	{ weapon = "arc9_cod2019_sh_origin12", ammo = 64 }, -- Origin 12 shotgun
	{ weapon = "arc9_cod2019_sh_model680", ammo = 60 }, -- model 680 shotgun
	{ weapon = "arc9_cod2019_sm_mp5", ammo = 60 }, -- MP5
	{ weapon = "arc9_cod2019_sm_p90", ammo = 100 }, -- P90
	{ weapon = "arc9_cod2019_sm_vector", ammo = 60 }, -- Vector
	{ weapon = "arc9_cod2019_ar_fal", ammo = 32 }, -- Fal
	{ weapon = "arc9_cod2019_ar_famas", ammo = 60 }, -- Famas
	{ weapon = "arc9_cod2019_ar_oden", ammo = 60 }, -- Oden
	{ weapon = "arc9_cod2019_ar_ak47", ammo = 60 }, -- Ak47
	{ weapon = "arc9_cod2019_ar_m4", ammo = 60 }, -- M4A1
	{ weapon = "arc9_cod2019_lm_mg34", ammo = 150 }, -- MG43
	{ weapon = "arc9_cod2019_lm_pkm", ammo = 200 }, -- PKM
	{ weapon = "arc9_cod2019_sn_ax50", ammo = 20 }, -- AX50
	{ weapon = "arc9_cod2019_sn_rytec", ammo = 40 }, -- AMR
	{ weapon = "arc9_cod2019_la_rpg", ammo = 4 }, -- RPG
	{ weapon = "arc9_cod2019_la_m32", ammo = 12 }, -- MGL
	{ weapon = "arc9_cod2019_mm_crossbow", ammo = 6 }, -- Crossbow
	{ weapon = "arc9_cod2019_nade_knife", ammo = 5 }, -- Knife
}

--[[-------------------------------------------------------------------------
This is the back-up weapons list that will be used during the game if somehow 
the above weapons list doesn't work.
---------------------------------------------------------------------------]]
GG_BACKUP_WEAPONS_LIST = {
	{ weapon = "weapon_357", ammo = 36 },
	{ weapon = "weapon_pistol", ammo = 36 },
	{ weapon = "weapon_smg1", ammo = 64 },
	{ weapon = "weapon_shotgun", ammo = 40 },
	{ weapon = "weapon_ar2", ammo = 100 },
	{ weapon = "weapon_crossbow", ammo = 10 },
	{ weapon = "weapon_rpg", ammo = 2 },
	{ weapon = "weapon_357", ammo = 36 },
	{ weapon = "weapon_pistol", ammo = 36 },
	{ weapon = "weapon_smg1", ammo = 64 },
	{ weapon = "weapon_shotgun", ammo = 40 },
	{ weapon = "weapon_ar2", ammo = 100 },
	{ weapon = "weapon_crossbow", ammo = 10 },
	{ weapon = "weapon_rpg", ammo = 2 },
	{ weapon = "weapon_357", ammo = 36 },
	{ weapon = "weapon_pistol", ammo = 36 },
	{ weapon = "weapon_smg1", ammo = 64 },
	{ weapon = "weapon_shotgun", ammo = 40 },
	{ weapon = "weapon_ar2", ammo = 100 },
	{ weapon = "weapon_crossbow", ammo = 10 },
}

--[[-------------------------------------------------------------------------
This is the secondary weapon which should be a melee weapon of some sort.

Note: If somehow the melee weapon down below doesn't work, the back-up melee
weapon will be used instead.
---------------------------------------------------------------------------]]
GG_KNIFE = "arc9_cod2019_me_knife"
GG_KNIFE_THROW = "m9k_thrown_spec_knife"

--[[-------------------------------------------------------------------------
This is the back-up melee weapon that will be used during the game if somehow 
the above melee weapon doesn't work.
---------------------------------------------------------------------------]]
GG_BACKUP_KNIFE = "weapon_crowbar"
GG_BACKUP_KNIFE_THROW = "weapon_crowbar"

--[[-------------------------------------------------------------------------
This is a list of skins that will be used during the game. You can add
whatever skin you want here but make sure that every client has the skins
installed, otherwise they'll only see errors.

Note: If somehow the skins in the list below don't work, the backup list will
be used instead. Leave this list untouched!
---------------------------------------------------------------------------]]
GG_SKINS_LIST = {
	"models/kyodementia/milsim_ar_PM.mdl",
	"models/kyodementia/milsim_dmr_PM.mdl",
	"models/kyodementia/milsim_lmg_PM.mdl",
	"models/kyodementia/milsim_sg_PM.mdl",
	"models/kyodementia/milsim_smg_PM.mdl",
	"models/kyodementia/milsim_sas_PM.mdl",
}

--[[-------------------------------------------------------------------------
This is a list of skins that will be used during the game if somehow the
skins in the list above don't work. Leave this list untouched!
---------------------------------------------------------------------------]]
GG_BACKUP_SKINS_LIST = {
	"models/player/urban.mdl",
	"models/player/gasmask.mdl",
	"models/player/riot.mdl",
	"models/player/swat.mdl",
	"models/player/leet.mdl",
	"models/player/guerilla.mdl",
	"models/player/arctic.mdl",
	"models/player/phoenix.mdl"
}

--[[-------------------------------------------------------------------------
The default number of minutes a round will take. You can also edit this in-game.
---------------------------------------------------------------------------]]
GG_ROUND_TIME_IN_MINUTES = 15

--[[-------------------------------------------------------------------------
The default amount of rounds a match has. You can also edit this in-game.
---------------------------------------------------------------------------]]
GG_AMOUNT_OF_ROUNDS_PER_MATCH = 5

--[[-------------------------------------------------------------------------
This is a list of usernames who can edit the game settings and start the 
match. If you leave the list empty, every player can start the match.

Note: If a player has admin rights but is not present in this list, he/she
can still start and control the game.

Example: GG_ALLOWED_PLAYERS = {
	"poepjejan1",
	"bluedragon102"
}
---------------------------------------------------------------------------]]
GG_ALLOWED_PLAYERS = {}

--[[-------------------------------------------------------------------------
MySQL Support. If enabled, certain game stats will be stored which can be
used later on by for example, a dashboard on a website.

Requirements to get this feature working:

- Have gmsv_tmysql4 installed on the dedicated server
	Windows: https://github.com/bkacjios/gm_tmysql4/releases/download/R1/gmsv_tmysql4_win32.dll
	Linux: https://github.com/bkacjios/gm_tmysql4/releases/download/R1.01/gmsv_tmysql4_linux.dll

	Install in "path/to/server/garrysmod/lua/bin/".
	(create the bin folder if it does not exist)

- Have libmysql/libmysqlclient installed on the dedicated server
	Windows: https://github.com/syl0r/MySQLOO/raw/master/MySQL/lib/windows/libmysql.dll
	Linux: https://github.com/syl0r/MySQLOO/raw/master/MySQL/lib/linux/libmysqlclient.so.18

	Install in "path/to/server/".
	(in the folder that contains srcds.exe or srcds_run)

Note: no pre-made website dashboard will be provided. You need to have 
programming knowledge to develop your own.
---------------------------------------------------------------------------]]
GG_USE_MYSQL = false
GG_MYSQL_HOST = "localhost"
GG_MYSQL_USERNAME = "username"
GG_MYSQL_PASSWORD = "password"
GG_MYSQL_DATABASE = "database"
GG_MYSQL_POST = 3306

--[[-------------------------------------------------------------------------
KEEP THIS DISABLED ON REAL SERVERS - FOR DEBUGGING ONLY!
---------------------------------------------------------------------------]]
GG_DEBUG = false
