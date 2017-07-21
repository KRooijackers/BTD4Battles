{
    "Upgrades":
    [
        {
            "Name": "Sharper Arrow",
            "WeaponUpgrade":
            {
            	"TaskUpgrade":
            	[
        			{
        				"Operation"		:	"SelectByType",
        				"Type"			:	"Projectile"
        			},
        			{
        				"Operation"		:	"Adjust",
        				"NumPersists"	:	1
        			}
            	]
            }
        },
        {
            "Name": "Razor Sharp Arrow",
            "WeaponUpgrade":
            {
            	"TaskUpgrade":
            	[
        			{
        				"Operation"		:	"SelectByType",
        				"Type"			:	"Projectile"
        			},
        			{
        				"Operation"		:	"Adjust",
        				"NumPersists"	:	2
        			}
            	]
            }
        },
        {
        	"Name":	"Destructive Arrow",
        	"WeaponUpgrade":
        	{
        		"TaskUpgrade":
        		[
        			{
        				"Operation"		:	"SelectByLocation",
        				"Location"		:	[ 0, 0 ]
        			},
        			{
        				"Operation"		:	"Replace",
        				"DamageType"	:	"Plasma"
        			},
        			{
        				"Operation"		:	"SelectByLocation",
        				"Location"		:	[ 0, 0 ]
        			},
        			{
        				"Operation"		:	"Adjust",
        				"Amount"		:	1
        			},
        			{
        				"Operation"		:	"SelectByLocation",
        				"Location"		:	[ 0, 2 ]
        			},
        			{
        				"Operation"		:	"Adjust",
        				"Amount"		:	2
        			},
        			{
        				"Operation"		:	"SelectByType",
        				"Type"			:	"Projectile"
        			},
        			{
        				"Operation"		:	"Replace",
        				"GraphicName"	:	"mmm_archer_arrow_destructive"
        			}
        		]
        	}
        },
        {
        	"Name":	"Crossbow",
        	"TowerUpgrade":
        	{
				"Weapons":
				{
					"0": "HydraRocketPods.weapon"
				}
        	}
        },
        {
        	"Name":	"Archer Discipline",
        	"WeaponUpgrade":
        	{
        		"Adjust":
        		{
        			"CooldownTime": -0.255
        		}
        	}
        },
        {
        	"Name":	"Archiplinity",
        	"TowerUpgrade":
        	{
        		"Replace":
        		{
        			"CanTargetCamo": true
        		}
        	},
        	"WeaponUpgrade":
        	{
        		"Adjust":
        		{
        			"CooldownTime": -0.325125
        		}
        	}
        },
        {
        	"Name": "Triple Arrow",
            "TowerUpgrade" :
            {
                "Weapons" :
                {
                    "0": "RayOfDoom.weapon"
                }
            }
        },
        {
        	"Name": "Fire Arrows",
            "TowerUpgrade" :
            {
                "Weapons" :
                {
                    "1": "RocketStorm.weapon",
                    "2": "RocketStormRockets.weapon"
                }
            },
        	"WeaponUpgrade":
        	{
        		"Adjust":
        		{
        			"CooldownTime": -0.05599375
        		},
        		
        		"TaskUpgrade":
        		[
        			{
        				"Operation"		:	"SelectByType",
        				"Type"			:	"Damage"
        			},
        			{
        				"Operation"		:	"Replace",
        				"DamageType"	:	"Plasma"
        			},
        			{
        				"Operation"		:	"SelectByType",
        				"Type"			:	"StatusEffect"
        			},
        			{
        				"Operation"		:	"Replace",
        				"Status"		:	"Napalm"
        			}
        		]
        	}
        }
    ]
}
