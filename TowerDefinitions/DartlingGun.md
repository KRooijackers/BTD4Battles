{
    "AircraftList"		      : [ ],

    "TypeName"				      : "DartlingGun",
    "Icon"					        : "dartling_gun_avatar_small",
    "Description"			      : "With a bow in his left and an arrow in his right, the Archer Monkey shoots at bloons like they're nothing.",
    "BaseCost"				      : 320,
    "RankToUnlock"		      : 18,
    "DefaultWeapons"	      : [ "DartlingGun.weapon" ],
	
    "TargetingMode"			    : "First",
    "RotatesToTarget"		    : true,
    "CanTargetCamo"			    : false,
    "TargetIsWeaponOrigin"	: false,
	
    "CanBePlacedInWater"	  : false,
    "CanBePlacedOnLand"		  : true,
    "CanBePlacedOnPath"		  : false,

    "UseRadiusPlacement"	  : true,
    "PlacementRadius"		    : 10.0,
    "PlacementW"			      : 0.0,
    "PlacementH"			      : 0.0,

    "SpriteUpgradeDefinition" : "DartlingGun.json",

    "Upgrades" : 
	[
        [
            "Sharper Arrow",
            "Razor Sharp Arrow",
            "Destructive Arrow",
            "Crossbow"
        ],
        [
            "Archer Discipline",
            "Archiplinity",
            "Triple Arrow",
            "Fire Arrows"
        ]
    ],
	"ShortUpgradeDescriptions" :
	[
		[
			"Each arrow can pop 1 extra bloons per shot.",
			"Each arrow can pop 2 extra bloons per shot.",
			"Each arrow pops 2 layers instead of 1. Can now pop Lead bloons and does bonus damage versus Ceramic bloons.",
			"Each arrow pops 3 layers instead of 2. Does bonus damage versus M.O.A.B. class and Ceramic bloons."
		],
		[
			"The Archer Monkey shoots faster.",
			"The Archer Monkey launches 2 arrows at the same time. It also makes the tower capable to target camo bloons.",
			"The Archer Monkey launches 3 arrows at the same time.",
			"The Archer Monkey shoots arrows that are on fire. Ability: ???"
		]
	], 
	"UpgradeDescriptions" :
	[
		[
			"Arrows have been sharpened. Go through more bloons now.",
			"Arrows became as sharp as glass. Even more bloons succumb by one arrow now.",
			"A more specialized arrow which bloons fear, even if they only hear about it!",
			"The power of the Crossbow combined with the specialized arrows makes it a true M.O.A.B. killer!"
		],
		[
			"As a result of hard work, Archer Monkey obtained the discipline to shoot faster and more accurate.",
			"Archer Monkey achieved a new level of discipline, which makes him capable to attack camoflage bloons.",
			"Legends say the Bloonjitsu taught the Archer Monkey to launch multiple arrows at once.",
			"The arrows are on fire! Ability: Shoots a rain of fire."
		]
	],
	"UpgradeGateway" :
	[
		[ { "Rank" : 0, "XP" : 0 }, { "Rank" : 0, "XP" : 0 }, { "Rank" : 0, "XP" : 0 }, { "Rank" : 0, "XP" : 0 } ],
		[ { "Rank" : 0, "XP" : 0 }, { "Rank" : 0, "XP" : 0 }, { "Rank" : 0, "XP" : 0 }, { "Rank" : 0, "XP" : 0 } ]
	],
    "UpgradePrices" : 
    [
        [ 120, 250, 1360, 3000 ],
        [ 140, 460, 2400, 2350 ]
    ],
    "UpgradeAvatars" :
    [
    	[ 
            "dartling_gun_avatar_focused_firing_small", 
            "dartling_gun_avatar_faster_barrel_spin_small", 
            "dartling_gun_avatar_laser_cannon_small", 
            "dartling_gun_avatar_ray_of_doom_small"
        ],
    	[ 
            "dartling_gun_avatar_powerful_darts_small", 
            "dartling_gun_avatar_bloontonium_small", 
            "dartling_gun_avatar_hydra_rockets_small", 
            "dartling_gun_avatar_bads_small"
        ]
    ],
    "UpgradeIcons" :
    [
    	[ 
            "dartling_gun_focused_icon", 
            "dartling_gun_faster_barrel_icon", 
            "dartling_gun_laser_icon", 
            "dartling_gun_ray_of_doom_icon" 
        ],
    	[ 
            "dartling_gun_powerful_darts_icon", 
            "dartling_gun_bloontonium_icon", 
            "dartling_gun_hydra_icon", 
            "dartling_gun_bads_icon" 
        ]
    ]                  
}
