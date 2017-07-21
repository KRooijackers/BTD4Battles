{	
    "Type"				: "DartlingGun",    
    "TargetRange"		: 140.0,
	"CooldownTime"		: 1.7,
    "FireDelayTime"		: 0.0,
    
    "Tasks" :
    [
		{
			"Type"						: "Projectile",
			"GraphicName"				: "mmm_archer_arrow_regular",
			"NumPersists"				: 2,
			"TerminateOnZeroPersists"	: true,
			"CollisionType"				: "Once",
			
			"Movement":
			{ 
				"Type"				: "Forward", 
				"Speed"				: 525.0, 
				"CutOffDistance"	: 350 
			},
            
			"Tasks":
			[
				{ 
					"Type"			: "Damage", 
					"DamageType"	: "Piercing", 	
					"Amount"		: 1 
				},
				{ 
					"Type"			: "Damage", 
					"DamageType"	: "Juggernaut", 
					"Amount"		: 0 
				},
				{ 
					"Type"			: "StatusEffect", 
					"Status"		: "MultiLayerDamage" 
				}
			]
		}
	]
}
