{	
    "Type"				: "RayOfDoom",    
    "TargetRange"		: 140.0,
	"CooldownTime"		: 1.7,
    "FireDelayTime"		: 0.0,
    
    "Tasks" :
    [
		{
			"Type"						: "MultiFire",
			"InitialOffset"				: -7,
			"AngleIncrement"			: 7,
			"FireCount"					: 3,
			
			"Tasks":
			[
				{
					"Type"						: "Projectile",
					"GraphicName"				: "mmm_archer_monkey_arrow_regular",
					"NumPersists"				: 2,
					"TerminateOnZeroPersists"	: true,
					"CollisionType"				: "Once",
					
					"SpreadAngle"				: 25,
					
					"Movement":
					{ "Type": "Forward", "Speed": 525.0, "CutOffDistance": 350 },
					
					"Tasks":
					[
						{ "Type": "Damage", "DamageType": "Piercing", "Amount": 1 },
						{ "Type": "StatusEffect", "Status": "", "DamageRate": 2.5, "Duration": 5 }
					]
				}
			]
		}
	]
}
