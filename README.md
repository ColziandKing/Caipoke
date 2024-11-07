# Calipole
ZZx one building gor all mods if so?

	{
		"name": "Hacienda",
		"uniqueTo": "Gran Colombia",
		"production": 1,
        "hurryCostModifier": 25,
		"cost": 77,
		"gold": 2,
		"uniques": [
			"[+1 Food] from every [Plantation] <before discovering [Replaceable Parts]>",
			"[+2 Food] from every [Plantation] <before discovering [Replaceable Parts]>",
			"[+3 Food] from every [Plantation] <before discovering [Replaceable Parts]>",
			"[+1 Food] from every [Plantation] <after discovering [Replaceable Parts]>",
			"[+1 Production] from every [Hacienda]> <before discovering [Replaceable Parts]>",
			"[+2 Production] from every [Hacienda] <before discovering [Replaceable Parts]>",
			"[+3 Production] from every [Hacienda] <before discovering [Replaceable Parts]>",
			"[+1 Production] from every [Hacienda] <before discovering [Replaceable Parts]>",
		]
	},
	{
		"name": "Kurgan",
		"uniqueTo": "Scythia",
		"faith": 1,
		"gold": 3,
        "hurryCostModifier": 25,
		"requiredTech": "Animal Husbandry",
		"uniques": [
			"[+1 Faith] from every [Pasture]",
			"[+1 Faith] from every [Pasture] <after discovering [Horseback Riding]>",
		]
	},
	{
		"name": "Mekewap",
		"uniqueTo": "The Cree",
		"production": 1,
		"gold": 2,
        "hurryCostModifier": 25,
		"cost": 57,
		"techRequired": "Pottery",
		"uniques": [
			"[+1 Food, +1 Production] <after adopting [Civil Service]>",
			"[+2 Gold] from every [Luxury resource] <after discovering [Navigation]>",
			"[+1 Food] from every [Bonus resource] <before adopting [Navigation]>",
			"[+2 Food] from every [Bonus resource] <before adopting [Navigation]>",
			"[+3 Food] from every [Bonus resource] <before adopting [Navigation]>",
			"[+1 Food] from every [Bonus resource] <after adopting [Navigation]>",
		]
	},
BuildingIcons/Hacienda
  rotate: false
  xy: 528, 85
  size: 100, 100
  orig: 100, 100
  offset: 0, 0
  index: -1
{
		"name": "Settler",
		"unitType": "Civilian",
		"requiredTech": "The Wheel",
		"movement": 2,
		"cost": 106,
		"uniques": ["Founds a new city <by consuming this unit>", "Excess Food converted to Production when under construction",
			"Requires at least [2] population"],
		"hurryCostModifier": 20
	},
