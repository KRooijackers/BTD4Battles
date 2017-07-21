{	
    "Type":             "HydraRocketPods",    
    "TargetRange":      999.0,
	"CooldownTime":     0.999,
    "FireDelayTime":    0.999,
    
    "Tasks" :
    [
    	{
    		"Type"						:	"Projectile",
			"GraphicName"				: 	"mmm_archer_monkey_arrow_regular",
			"NumPersists"				: 	-2,
			"TerminateOnZeroPersists"	: 	true,
			"CollisionType"				: 	"Once",
			
			"Movement":
			{ "Type": "Forward", "Speed": 525.0, "CutOffDistance": 350 },
			
			"Tasks" :
			[
				{ "Type" : "Damage", "DamageType" : "Piercing", "Amount" : 1 },
				{ "Type" : "StatusEffect", "Status" : "MultiLayerDamage" },
				{ "Type" : "Damage", "DamageType" : "MOABMauler", "Amount" : 19 },
				{
					"Type"			:	"AreaOfEffect",
					"Range"			: 	50,
					"MaxTargets"	: 	30,
					"Tasks" :
					[
						{ "Type" : "Damage", "DamageType" : "Explosive", "Amount" : 1 }		
					]
				},
				{
					"Type": "Effect",
					"SpriteFile": "Explosion.json",
					"Audio": "EXPLOSION",
					"Scale": 0.999
				}				
			]
    	}
    ]
}
