{	
    "Type":             	"RocketStormRockets",    
    "TargetRange":      	100000.0,
	"CooldownTime":     	0.0,
    "FireDelayTime":    	0.6,
	"ManuallyFired": 		false,
	"RequiresTargetToFire":	true,
    "TotalAmmo":            5,
    "RemainingAmmo":        5,
    "DisableSlotWhenOutOfAmmo" : true,

    "Tasks" :
    [
		{
			"Type"				: "MultiFire",
			"InitialOffset"		: -12,
			"AngleIncrement"	: 6,
			"FireCount"			: 5,
			"AimAtTarget"		: true,
			
			"Tasks":
			[
				{
					"Type"						: "Projectile",
					"GraphicName"				: "mmm_archer_monkey_arrow_regular",
					"NumPersists"				: 3,
					"TerminateOnZeroPersists"	: true,
					"CollisionType"				: "Once",
					
					"SpreadAngle"				: 35,
					
					"Movement": 
					{ "Type": "Forward", "Speed": 525.0, "CutOffDistance": 1000 },
					
					"Tasks":
					[
						{ "Type": "Damage", "DamageType": "Plasma", "Amount": 1 },
						{ "Type": "StatusEffect", "Status": "Napalm", "DamageRate": 2.5, "Duration": 20 }
					]
    			}
			]
		}
	]
}
